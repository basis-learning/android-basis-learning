# Android Boot Process

A simple summary and study notes for android boot process.

Main content please see other files in this directory.

[Keynote](./android-boot-process.key) / [PDF](./android-boot-process.pdf)

## Table of Contents

* [Q & A](#q--a)
	* [use space & kernel space](#use-space--kernel-space)
* [Related knowledge](#related-knowledge)
	* [Internal RAM](#internal-ram)

## Q & A

### use space & kernel space

Reference: [Wikipedia: User space](https://en.wikipedia.org/wiki/User_space)

> A modern computer operating system usually segregates virtual memory into kernel space and **user space**. Primarily, this separation serves to provide memory protection that protects data and functionality from faults (by improving fault tolerance) and malicious behaviour (by providing computer security).
> 
> **Kernel space** is strictly reserved for running a privileged operating system kernel, kernel extensions, and most device drivers. In contrast, user space is the memory area where application software and some drivers execute.

## Related knowledge

### Internal RAM

Reference: [Wikipedia: Internal RAM](https://en.wikipedia.org/wiki/Internal_RAM)

> **Internal RAM**, or IRAM, is the address range of RAM that is internal to the CPU. Some object files contain an .iram section.
> 
> Generally, IRAM is composed of very high speed SRAM located alongside of the CPU. It acts similar to a CPU cache, but is software addressable. This saves transistors and power, and is potentially much faster, but forces programmers to specifically allocate it in order to benefit. In contrast, cache is invisible to the programmer.
