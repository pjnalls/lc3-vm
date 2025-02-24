# LC-3 VM

### (Little Computer 3 as a Virtual Machine)

a vitural machine (VM) built by following the tutorial provided by Justin Meiners and Ryan Pendleton for understanding how computers work. Please click on the link below for the original source code.

[https://www.jmeiners.com/lc3-vm/](www.jmeiners.com/lc3-vm/)

## Getting Started
1. Ensure you have the GCC compiler installed on your machine.
```bash
$ gcc -v
```
2. Ensure Python version 3 is installed on your machine.
```bash
$ python -V
```
3. Create the executable for the VM:
```bash
$ gcc lc3.c -o lc3-vm
```
4. Use an LC-3 assembler written in Python to assemble an Assembly program (e.g., `2048.asm`).
```bash
$ python3 lc3-nasm.py 2048.asm
```
5. Run the executable with the machine code object file to test the VM.
```bash
$ ./lc3-vm 2048.obj
```
