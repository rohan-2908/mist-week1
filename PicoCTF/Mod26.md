# Mod 26

Cryptography challenge involving a cipher known as ROT13.<br>

[Chalenge LInk](https://play.picoctf.org/practice/challenge/144)

<br>

### Solving
The challenge description provided a string that looked like a flag but with the letters rotated. The title "Mod 26" hints at modular arithmetic on the 26-letter alphabet. Since ROT13 rotates by exactly half (13), I used the online tool [rot13.com](https://rot13.com/). I simply pasted the encrypted string into the input box and it decoded the flag instantly.<br>

<br>

### Flag
> picoCTF{next_time_I'll_try_2_rounds_of_rot13_aFxtzQWR}
