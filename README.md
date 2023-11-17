# Encryption
These files are simple command-line programs in C that take in a passowrd and encrypt it for security. Both of these programs were created as part of an assignment for a computer science course that I took while in college at Harvard University.

## Caesar
Legends say that Caesar used to encrypt confidential messages by shifting each letter by a certain number *k* places. Thus, with a key *k* of 1, "a" becomes "b," "b" becomes "c," and so on. This is a command-line program that prompts users for a plaintext messagae, a positive integer for a key, and then prints the ciphertext. 

For example, when running "./caesar 1" and inputting "HELLO," the printed plaintext would be "IFMMP."

## Substitution
The substitution cipher encrypts confidential messages by replacing every letter with another letter. To decrypt the message, the receiver would have to know the key. 

This is a command-line program that users run using "./substitution *key*". For example, a key like "YTNSHKVEFXRBAUQZCLWDMIPGJO" would map "Y" to "A," "T" to "B," and so on. 

Thus, for running "./substitution YTNSHKVEFXRBAUQZCLWDMIPGJO" and inputting "HELLO" when prompted for the ciphertext, the printed plaintext would be "EHBBQ."

## Usage
In order to run the program, users will need to download the [CS50 library](https://github.com/cs50/libcs50/releases) and follow these [instructions](https://github.com/m-saylor/libcs50). The code must then be compiled.

Casesar Usage: "./caesar *key*" with *key* being a positive integer that indicates how many places to shift each letter by

Substitution Usage: "./substitution *key*" with *key* representing all 26 letters of the alphabet that map directly to the standard alphabet
