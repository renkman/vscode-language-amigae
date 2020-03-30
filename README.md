# Amiga E extension for Visual Studio Code

A [Visual Studio Code](https://code.visualstudio.com/) [extension](https://marketplace.visualstudio.com/VSCode) wich provides code highlighting for [Amiga E](http://strlen.com/amiga-e/).

When I started to learn Amiga E with [FS-UAE](https://fs-uae.net/) and the original Amiga E compiler by [Wouter van Oortmerssen](http://strlen.com/) (available on [Aminet](http://aminet.net/dev/e)), 
I have mounted a host directory as harddisk on the emulator for the source code and edited my .e source files with Visual Studio Code. Unfortunately, there was no Amiga E extension for the editor available (Suggestions 
made by Visual Studio Code for .e files and a search in the Marketplace led to no result).

Thus I just created this extension to access proper highlighted code for my Amiga E experience.

## Features

This extension enables code highlighting for the Amiga E programming language in Visual Studio Code.

![syntax](images/code-highlighting_dark.png)
![syntax](images/code-highlighting_light.png)

## Release Notes

The first draft of the grammar is now ready for testing.

### 0.1.4

- Added SELECT .. OF block syntax

### 0.1.3

- Fixed IF grammar bug
- Added grammar for SELECT block and LOOP block
- Added keywords SIZEOF, DEC, INC, JUMP and EXIT

### 0.1.0

- Code and syntax highlighting for Amiga E is implemented