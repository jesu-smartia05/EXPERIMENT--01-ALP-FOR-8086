# EXPERIMENT--01-ALP-FOR-8086
Name : Jesu Smartia A
Roll no : 212223110016
Date of experiment : 





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
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







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
ORG 100h
MOV ax,11h;
MOV bx,20h;
ADD ax,bx;
HLT
```

## Output  
 ![363826756-1f8716da-ed9f-4ccf-b657-f08bbe0b4bad](https://github.com/user-attachments/assets/033b47df-4788-493f-b343-871d7c1bb12d)

## Subtraction   of 8 bit numbers  ALP 
 ```
ORG 100h
MOV ax,11h;
MOV bx,20h;
SUB ax,bx;
HLT
```
## Output  
![363826015-1901a10a-b120-4287-a28e-13a0027414bd](https://github.com/user-attachments/assets/4e165011-be89-4536-86ab-9ebfaa8305c1)

## Multiplication alp 
```
ORG 100h
MOV ax,31h;
MOV bx,20h;
MUL bx;
HLT
```
 ## Output  
![363826205-9c8ad22d-7a5a-4883-8ff3-8cdce0c0077f](https://github.com/user-attachments/assets/fc9a884e-b3b7-44ee-be32-a06b489918f0)

## Division alp 
```
ORG 100h
MOV ax,31h;
MOV bx,20h;
DIV bx;
HLT
```
## Output   
![363826301-292f3adf-bb87-41a9-999b-c458bdeca778](https://github.com/user-attachments/assets/72817ff8-6457-4805-86a4-460d0613c60a)

## Logical Operations
# Logical AND
```
MOV AL,53H
MOV BL,24H
AND AL,BL
HLT
```
## Output
![370113180-7cbc943a-39d9-4bfd-99a1-951ae25ceac8](https://github.com/user-attachments/assets/872416b5-be20-44d1-9500-3123d363562c)

## Logical OR
```
MOV AL,53H
MOV BL,24H
OR AL,BL
HLT
```
## Output
![370113452-a4112932-17c2-4bfd-9103-bb17d77b6df5](https://github.com/user-attachments/assets/8857d506-4e15-4a9d-9530-3f1028b51749)

## Logical NOT
```
MOV AL,53H
NOT AL
HLT
```
## Output
![370113729-5ce9b2aa-9cc3-4641-a3d0-a02636aefca0](https://github.com/user-attachments/assets/8ac04caa-9c1e-432d-92aa-00871c1a20a3)

## Logical XOR
```
MOV AL,53H
MOV BL,24H
XOR AL,BL
HLT
```
## Output
![370114257-25806f01-f75b-4faf-8cc9-0680ec6a8e13](https://github.com/user-attachments/assets/a90e748c-7dc2-44a2-a93c-8897207b35ff)

## Result :
 Thus, To write and execute ALP on fundamental arithmetic operations is successful.










