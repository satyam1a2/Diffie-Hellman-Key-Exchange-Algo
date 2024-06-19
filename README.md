# Diffie-Hellman-Key-Exchange-Algo
# Secure Communication Program

This program demonstrates secure communication using symmetric key encryption. It generates random prime numbers, performs key exchange, and encrypts/decrypts a file using symmetric keys.

## Overview

- **isprime:** Checks if a given number is prime.
- **genrandomprime:** Generates a random prime number in a specified range.
- **secure:** Computes g^x mod n to generate a secure key.
- **encryptFile:** Encrypts a file using a symmetric key.
- **decryptFile:** Decrypts a file using a symmetric key.
- **clearScreen:** Clears the console screen.
- **changeTextColor:** Changes text color in the console.
- **printHeading:** Prints a heading with blue color.
- **printMessage:** Prints a message with green color.

## Usage

1. Run the program.
2. Enter private numbers for person 1 and person 2.
3. Public keys are generated and exchanged.
4. Secure keys (symmetric) are computed.
5. A file is encrypted by person 1 using K1 and sent to person 2.
6. Person 2 decrypts the file using K2.

## Compilation and Execution

Compile the program using a C compiler:
