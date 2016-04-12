# FLOSS test: test-decode-single-byte-xor

Purpose: Demonstrate decoding of a single byte xor routine.
Decoding algorithm: single byte xor
Input buffer location: stack
Output buffer location: stack

Decoded strings:
hello world

Source files:
test-decode-single-byte-xor.c

Build instructions (Windows):
eg. cl.exe test-decode-single-byte-xor.c /Fetest-decode-single-byte-xor.exe

Build instructions (Linux):
eg. clang test-decode-single-byte-xor.c -o test-decode-single-byte-xor

Build instructions (Cross compile for Windows on Linux):
i686-w64-mingw32-clang test-decode-single-byte-xor.c -o test-decode-single-byte-xor.exe