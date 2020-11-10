# Stack-BoF
A stack buffer overflow exercise

It was assigned by Professor Tassos Dimitrio in Kuwait University and completed with the group member Eng. Amna Jasser 

This exercise has a buffer overflow vulnerability mainly in “stack.c” and specifically inside the bof method. The vulnerability exists at the strcpy function call, it copies content of size 512 bytes into a 12-byte buffer, and because this function does not make checks on the sizes of the buffers before copying, it can be exploited to mount a buffer overflow attack. The buffer to be overflowed in this case is the 12-byte buffer. A 517-byte buffer initialized with no operation instructions (NOPs) shall be used to complete this task. This buffer must be filled with the right content to succeed.
