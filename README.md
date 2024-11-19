Library Management System, Autumn 2024 Final Project


This is the documentation for CS3101 2024 project by Team Haringhata IT Cell (Abhratanu Ray (22MS052) and Niravra Nag (22MS072). 

The project has 3 .c files, 2 header files, a bookdata file which stores current book stock, and an admin log through which admin can check past actions by users. The system needs to be run by executing an object for main.c after compiling other 2 files whose functions have been included in main.c through header files.

Put the following files in the same directory:
backend.c
chatbot.c
main.c
backend.h
chatbot.h

The program was created in VSCode user setup version 1.95.3, with a gcc (MinGW.org GCC-6.3.0-1) 6.3.0 port, on a Windows 10 system.
Preferably, the program should be run in the same way, in VSCode, via MinGW. This is because different terminals have different default settings, especially in case of stdin flushing. This may cause various issues when the code is run in different terminals, where inputs may leak into other fgets statements, and prevent the user from inputting later fields.

To run, execute:

gcc main.c backend.c chatbot.c -o main

Then, run:

.\main

 The program should run, and be self explanatory. Initially, no student users are registered. Please first register, to sign in as a student.
The only faculty ID is ”kripa”, with password “bandhu”.
Admin password is “haringhataITcell”.
All passwords are case sensitive.

References:

The C Programming Language (1978) - Brian Kernighan and Dennis Ritchie
The WeLearn Material Provided by Prof. Kripabandhu Ghosh for CS3101, during Autumn 2024
