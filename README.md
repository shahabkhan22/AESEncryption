# AESEncryption


Advanced Encryption Standard(AES) Algorithm implemented in Python
This implementation is for the Cipher Block Chaining(CBC) Mode

CBC Mode Brief Explanation- 

In CBC Mode each plaintext block is XORed with the previous Ciphertext Block before encryption. Hence the ciphertext block is dependent on all the plaintext blocks before it.

A plaintext message M is divided into t n-bit blocks M[i] and Ciphertext C[i] is given by -
          C[i] = E[k](M[i] XOR C[i-1]),    i=1,2,3,....,t     E = current block

This is done in CBC Mode to randomize the data blocks to hide patterns and repitions.

The first ciphertext block,C[0], i.e. the initial block of data that is XORd with first message block M[1] is called Initialization Vector(IV) and it is randomly chosen to be used for decryption.


Change the code as needed for length of key
Supports all key lengths - 128/196/256


Input - Plaitext String, Key
Output - Ciphertext




Created as Internal Project during Internship in February 2018
Will add comments in code in time. Trust Me. I promise. ;)
