# ManyTimePad
Let us see what goes wrong when a "one-time" pad is used more than once.

The file "ciphertexts.txt" contains some hex-encoded ciphertexts that are the result of encrypting some ASCII messages with the same pad.
Your goal is to decrypt these ciphertexts, and submit the secret message and the program you've written to crack the code, along with its documentation.

Note:
1) Cleartext messages contain only letters and spaces
2) As explained during lecture, the key idea to crack this code is considering what happens when a space is XORed with a (uppercase/lowercase) letter

The idea for this exercise has been taken from the excellent course "Cryptography I" on Coursera (https://www.coursera.org/course/crypto)

If you use Python to tackle the challenge, you may find the following resources useful:
https://docs.python.org/3/library/argparse.html
https://docs.python.org/3/library/binascii.html
https://docs.python.org/3/library/stdtypes.html#string-methods
https://docs.python.org/3/library/functions.html#func-range
https://docs.python.org/3/library/functions.html#enumerate
https://docs.python.org/3/reference/expressions.html#binary-bitwise-operations
