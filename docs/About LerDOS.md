# About LerDOS
In this document, you will learn about what softwares compose LerDOS, and learn some stuff about them.


## 1. The Kernel (MCKernel)
MCKernel is the most fundamental part of LerDOS. It works along with Limine to provide graphics, input and the memory allocation. Its written in C with some parts of Assembly, and compiled with x86_64-elf-g++.

## 2. The Shell (Kish)
Kish is the shell that is integrated in the kernel. It has the Zbra scripting language, which is closely inspired by BASIC ideals and logic. It will be replaced by a POSIX-compliant shell later on, which wont be integrated on the kernel.

## 3. The Tools (Goreutils)
Goreutils is the coreutils equivalent for LerDOS, even though Kish is not POSIX-compliant. It has commands like cd, ls, pwd, mostly directory related. Will be expanded, replaced or rewrited once we have a POSIX-compliant shell.

## 4. The GUI (Guiguibaby)
Guiguibaby is the GUI/DE for LerDOS. It is going to be part of the OS once we have a solid kernel, a proper POSIX-compliant shell and a good repertory of syscalls. No mouse though.

## 5. The GUI tools (BeQedb, Bife e Queijo encima da bolachinha)
BeQedb is composed of a text editor (Thomas), a PC Speaker music thing (PSmt) and an image viewer (Grohl)


**this stuff will probably change. we are still early in development. we have time to develop it, we are in no hurry.
