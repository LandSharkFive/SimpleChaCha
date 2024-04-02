# Simple Cha Cha

This program is a simple implementation the Cha Cha encryption algorithm.  The program encrypts and decrypts a paragraph using Cha Cha.

## Install and Build

The is a C# Console-Mode Project.  Open with  Visual Studio 2022 and above to compile. 

## Description:

A simple encryption and decryption program using the Cha Cha algorithm.  

## Warning

This program is for Educational Purposes only.  In order to be secure, the Nonce must be unique for each message that is sent.  Never use the same Nonce value twice.  Using the same Nonce twice will expose the keys, IV and nonces.  The basis of the Cha Cha algorithm is simple exclusive or with a plain text messages.

## Files

A references.txt file is included for more information about the Cha Cha algorithm.  A sample.txt file displays a sample run of the program.

## Enchancements

Several enchancements are deliberately not included in the code.  These enhancements are left as exercises.  The enchancements include:  1305 Poly MAC header,  Sub-Key Generation and implementing secure containers for the Key, IV and nonces. 

