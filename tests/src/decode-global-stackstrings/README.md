# FLOSS test: test-decode-global-stackstrings

Purpose: Demonstrate extraction of "global stackstrings".
Decoding algorithm: stackstrings
Input buffer location: n/a
Output buffer location: global

Decoded strings:
goodbye world

Source files:
test-decode-global-stackstrings.c

Build instructions (Windows):
cl.exe test-decode-global-stackstrings.c /Fetest-decode-global-stackstrings.exe

Build instructions (Linux):
clang test-decode-global-stackstrings.c -o test-decode-global-stackstrings

Build instructions (Cross compile for Windows on Linux):
i686-w64-mingw32-clang test-decode-global-stackstrings.c -o test-decode-decode-stackstrings.exe