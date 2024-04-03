# Simple Cha Cha

This program is a simple implementation the Cha Cha encryption algorithm.  The program encrypts and decrypts a paragraph using Cha Cha.

## Install and Build

The is a C# Console-Mode Project.  Open with  Visual Studio 2022 and above to compile. 

## Description:

A simple encryption and decryption program using the Cha Cha algorithm.  

## Warning

This program is for Educational Purposes only.  In order to be secure, the Nonce must be unique for each message that is sent.  Never use the same Nonce value twice.  Using the same Nonce twice will expose the keys, IV and nonces.  The basis of the Cha Cha algorithm is simple addition with a plain text messages.

## Files

For more information on the Cha Cha algorithm, see the references.txt file. A sample run of the program is in the sample.txt file.

## Enchancements

Several enchancements are deliberately not included in the source code.  These missing enhancements are left as exercises.  The missing enchancements include 1305 Poly MAC header, Padding, Sub-Key Generation and implementing Secure Containers for the key. 

