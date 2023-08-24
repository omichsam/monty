# 0x19. C - Stacks, Queues - LIFO, FIFO

## Description

### The Monty language
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

#### Monty byte code files

Files containing Monty byte codes usually have the .m extension. Most of the industry uses this standard but it is not required by the specification of the language. There is not more than one instruction per line. There can be any number of spaces before or after the opcode and its argument:

## Environment

Ubuntu 14.04 LTS via Vagrant in VirtualBox and compiled with GCC version 4.8.4

## Instructions

### Resources:books:
Read or watch:
* [Google](https://intranet.hbtn.io/rltoken/56-bDz7IrFgcH02EkGkB3w)
* [Create dynamic libraries on Linux](https://intranet.hbtn.io/rltoken/9neX6gaN6DoA-ow1INgZqw)


### Learning Objectives:bulb:
What you should learn from this project:

* What do LIFO and FIFO mean
* What is a stack, and when to use it
* What is a queue, and when to use it
* What are the common implementations of stacks and queues
* What are the most common use cases of stacks and queues
* What is the proper way to use global variables

### Intructions basics

-   Compiling the program: `gcc -Wall -Werror -Wextra -pedantic *.c -o monty`
