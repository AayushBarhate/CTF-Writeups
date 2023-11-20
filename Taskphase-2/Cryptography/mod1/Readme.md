# base mod1 Writeup

## Challenge Overview

Encountering a mysterious message passed around on the servers, I delved into decrypting it using the provided `decrypt.c` file. The task involved taking each number in the message, applying a modulo operation with 37, and mapping the result to a character set. The character set comprised uppercase letters for values 0-25, decimal digits for values 26-35, and underscore for value 36.

## Solution Approach

1. **Decryption Script (`decrypt.c`):**
   - The provided `decrypt.c` script appeared to outline the decryption scheme.

2. **Mapping Numbers to Characters:**
   - I followed the instructions, taking each number in the message and applying a modulo operation with 37.
   - Mapped the resulting values to the specified character set.

3. **Flag Formatting:**
   - Wrapped the decrypted message in the picoCTF flag format: `picoCTF{decrypted_message}`.

## Flag

The decrypted message, formatted as the flag, is:

`picoCTF{R0UND_N_R0UND_79C18FB33}`
