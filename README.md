# Amiga E extension for Visual Studio Code

A [Visual Studio Code](https://code.visualstudio.com/) [extension](https://marketplace.visualstudio.com/VSCode) wich provides syntax highlighting and code snippets for [Amiga E](http://strlen.com/amiga-e/).

When I started to learn Amiga E with [FS-UAE](https://fs-uae.net/) and the original Amiga E compiler by [Wouter van Oortmerssen](http://strlen.com/) (available on [Aminet](http://aminet.net/dev/e)), 
I have mounted a host directory as harddisk on the emulator for the source code and edited my .e source files with Visual Studio Code. Unfortunately, there was no Amiga E extension for the editor available (Suggestions 
made by Visual Studio Code for .e files and a search in the Marketplace led to no proper result).

Thus, I just decided to create an extension for Amiga E.

## Features

This extension enables code highlighting and provides code snippets for the Amiga E programming language in Visual Studio Code.

![syntax](images/code-highlighting_dark.png)
![syntax](images/code-highlighting_light.png)

## Release Notes

Several grammar fixes and introduction of code snippets.

### 0.2.0

 - Introduced code snippets for function, class and the loop types
 - Fixed and enhanced grammar
    - Added RETURN, VOID and SET keywords
    - Added types for variable declaration

### 0.1.7

- Fixed and completed object and member modifiers

### 0.1.4

- Added SELECT .. OF block syntax

### 0.1.3

- Fixed IF grammar bug
- Added grammar for SELECT block and LOOP block
- Added keywords SIZEOF, DEC, INC, JUMP and EXIT

### 0.1.0

- Code and syntax highlighting for Amiga E is implemented