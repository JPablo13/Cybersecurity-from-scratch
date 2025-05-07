# Buffer Overflow

This is an anomaly that occurs when software writing data to a buffer overflows its capacity, causing adjacent memory locations to be overwritten. Cybercriminals exploit this anomaly to modify a computer's memory to undermine or take control of program execution.

## What is a buffer?
It is a physical memory storage area used to temporarily hold data while it is being moved from one location to another. These buffers are usually located in RAM.

## How do they exploit this?
Deliberately introducing carefully crafted input into a program will cause it to attempt to store that input in a buffer that is not large enough, overwriting portions of memory connected to the buffer space.

## Examples

### Stack buffer overflow attack *
This is the most common type of attack in this branch and involves overflowing the buffer on the call stack or memory stack.

### Heap buffer overflow attack *
This attacks data in the open memory pool known as the heap.

### Integer overflow attack
This is not a buffer overflow, but it can lead to one. This occurs when an arithmetic operation produces a result greater than the maximum value that an integer data type can store.

### Unicode overflow
Creates a buffer overflow by inserting Unicode characters into an input that expects ASCII characters.

*Computers are based on two different memory allocation models, known as the stack and the heap, both of which are located in RAM. *