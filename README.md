# EazDecode
A program for decoding EazFuscator stacktraces.

## Note
This program does not allow you to decrypt symbols you don't have the password for. As such, it is only useful in a limited amount of cases (i.e. with past source leaks).

All functionality in this progran is also present in the official EazFuscator SDK, however since the SDK will re-initialize its RNG every decryption cycle, it is very slow. This library does not have this limitation, allowing it to decrypt thousands of symbol names in under a second.
