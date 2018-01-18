# Important-Linux-Commands
Essential Linux commands for compiling codes


Could not get lock:

sudo rm /var/lib/apt/lists/lock 

sudo rm /var/cache/apt/archives/lock 

sudo rm /var/lib/dpkg/lock


Client Server run:

g++ -o server server.cpp

./server portnumber

g++ -o client client.cpp

./client hostname(ip) portnumber


NASM compile assembly:

nasm -f elf -o asm1.o asm1.asm

gcc -o asm1 asm1.o

gcc -m32 -o asm1 asm1.o (Alternative-sudo apt-get install gcc-multilib﻿)

./asm1


