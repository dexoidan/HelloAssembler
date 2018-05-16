# Hello Assembler

I will sharing all my assembly files that I am able to compile in a operating system.

It is not my goal to provide any tools that can be used to penetration testing, but i dont know if you are using my stuff to this.

Compilation procedure for Linux environment

Compile hello-world-minimal.c:

	gcc hello-world-minimal.c -o helloworld_bin
	chmod +x helloworld_bin

Compile helloword.asm
	
	nasm -f elf64 helloworld.asm
	ld helloworld.o -o helloworld
	chmod +x helloworld

It is interesting that C compiled source code is bigger in size than program code that is written in Assembly.