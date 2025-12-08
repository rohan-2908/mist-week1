## Interencdec

A multi-layer cryptography challenge involving Base64 and Caesar ciphers.<br>

[Here is the challenge Link](https://play.picoctf.org/practice/challenge/73)

<br>

### Solving
I downloaded the file and used CyberChef (an online analysis tool) to decode the layers without writing code:
1. I pasted the file content (`YidkM0JxZGtwQlRYdHFhR3g2YUhsZmF6TnFlVGwzWVROclh6ZzJhMnd6TW1zeWZRPT0nCg==`) into CyberChef.
2. I added the **"From Base64"** recipe. The output was a second Base64 string.
3. I added a second **"From Base64"** recipe. The output was `wpjvJAM{jhlzhy_k3jy9wa3k_86kl32k2}`.
4. I added a **"Caesar Cipher"** (or ROT13) recipe and adjusted the shift amount (Shift 19 or -7) to shift the letters back to `pico`.<br>

<br>

### Flag
> picoCTF{caesar_d3cr9pt3d_86de32d2}
