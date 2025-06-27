# Even RSA can be broken
By connecting to the host using nc verbal-sleep.picoctf.net 58750, we receive N, e, and the ciphertext c. Using these values with an RSA decryption tool, we are able to recover the flag.

# Flag
picoCTF{tw0_1$_pr!m33991588e}