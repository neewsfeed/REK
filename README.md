# REK
REK is an x86-64 microkernel operating system made in C++ from scratch. The name is a joke btw, It was meant to mean: Reverse Engineering Kernel, but it's clearly not anything like that 🤣
<br>

REK IS:
- Secure. It makes some already existing security measures as non-optional (ASLR, RELRO, NX stack...). Plus, the whole memory layout of the kernel is designed to be resistant to Meltdown and Spectre attacks.
- Beautiful. When possible and appropiate, REK gives simple solutions to complex problems, even if they're not the absolute fastest. I've done my very best to write easy to read code. Note, however, that the code is not a tutorial, do not take everything I do as the best solution, or even a good one. Have your own judgment.
- Modular. REK is not, unlike most hobbyist operating systems, a repository with thousands of files that all have to be compiled in order to get an ISO. It is an anarchic collection of drivers, services, tools, and a kernel, of course. Because of this, you choose what goes in and what's left out.

