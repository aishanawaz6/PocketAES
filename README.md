# PocketAES CLI Programs

This repository contains three command-line interface (CLI) programs written in Python to demonstrate various aspects of the PocketAES encryption algorithm. PocketAES is used for encryption and decryption tasks, including handling individual blocks of data and decrypting ASCII text.

## Program 1: PocketAES Encryption Stages

### Description
This program showcases the different stages of PocketAES encryption. It prompts the user for a text block and a key, both in 16-bit hexadecimal format. Then, it computes and displays the outputs of the SubNibbles, ShiftRow, MixColumns, and GenerateRoundKeys operations on these inputs.

## Program 2: PocketAES Block Decryption

### Description
This program decrypts a single block of ciphertext using the PocketAES algorithm described in Section A. It receives the ciphertext and the encryption key as hexadecimal inputs from the user and outputs the decrypted block in the same hexadecimal format.

## Program 3: ASCII Text Decryption

### Description
This program implements the ASCII text decryption scheme defined in Section B. It reads encrypted text from a file named 'secret.txt,' decrypts it using the provided encryption key, and creates an output file named 'plain.txt.' The input contains a series of ciphertext blocks in hexadecimal format, and the output data is in ASCII text. The program handles null padding that may be present in the ciphertext.

## Security Analysis
### Description
Analyzed the encryption scheme discussed in Section B to see if it has any security flaws?

Feel free to explore and use these programs to understand and work with the PocketAES encryption algorithm.
