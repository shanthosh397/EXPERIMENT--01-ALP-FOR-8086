# EXPERIMENT--01-ALP-FOR-8086

Name : Shanthosh.G

Reg no : 2305003008 

Date of experiment :





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations-
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :-
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations :-

## ADDITION of 8 bit ALP :
MOV AL,13H  
MOV BL,24H  
ADD AL,BL  
HLT  

## Output :
![Screenshot (11)](https://github.com/user-attachments/assets/22bf09de-5246-4d2e-8a58-845455e2470d)

## SUBTRACTION of 8 bit ALP :

MOV AL,84H
MOV BL,63H
SUB AL,BL
HLT

## Output :
![Screenshot (12)](https://github.com/user-attachments/assets/70d43480-6dea-4a26-a12b-8e8f0b670c36)

## MULTIPLICATION of 8 bit ALP :

MOV AL,75H
MOV BL,32H
MUL BL
HLT

## Output :
![Screenshot (13)](https://github.com/user-attachments/assets/f3b1465a-e41a-4639-8e72-def77685acbd)

## DIVISION of 8 bit ALP :

MOV AL,68H
MOV BL,18H
DIV BL
HLT

## Output :
![Screenshot (14)](https://github.com/user-attachments/assets/1fab9276-8f29-4bed-9b7c-4696c3a7f34e)

## AND of 8 bit ALP :

MOV AL,33H
MOV BL,44H
AND AL,BL
HLT

## Output :
![Screenshot (15)](https://github.com/user-attachments/assets/bf590f37-b3cf-4a7f-b706-4782977d2d83)

## OR of 8 bit ALP :

MOV AL,45H
MOV BL,66H
OR AL,BL
HLT

## Output :
![Screenshot (16)](https://github.com/user-attachments/assets/13585384-9d81-485d-af7e-3a46f89c7494)

## NOT of 8 bit ALP :

MOV AL,65H
NOT AL
HLT

## Output :
![Screenshot (17)](https://github.com/user-attachments/assets/fb7e7535-e098-48df-8b41-3670a4294775)

## XOR of 8 bit ALP :

MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT

## Output :
![Screenshot (18)](https://github.com/user-attachments/assets/d10829d6-adbb-4f82-850e-05a9ca121425)

## Result :-
Thus to Write and execute ALP on fundamental arithmetic and logical operations are verified successfully.
