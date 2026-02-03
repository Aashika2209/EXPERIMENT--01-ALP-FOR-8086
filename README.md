# EXPERIMENT--01-ALP-FOR-8086
## Name : AASHIKA JAIN G
## Roll no : 212224110001
## Date of experiment : 03-02-2026

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
org 100h
MOV AL,74H
MOV BL,39H
ADD AL,BL
HLT
```

## Output  
<img width="1109" height="763" alt="image" src="https://github.com/user-attachments/assets/bf38b50f-5f51-4d84-b151-4a34627efa5d" />

## Subtraction   of 8 bit numbers  ALP 
```
org 100h
MOV AL,68H
MOV BL,19H
SUB AL,BL
HLT
```
## Output  
<img width="1106" height="776" alt="image" src="https://github.com/user-attachments/assets/1d3ca46f-7cd3-4aae-ae10-e71051263334" />

## Multiplication alp 
```
org 100h
MOV AL,10H
MOV BL,59H
MUL BL
HLT
```
 ## Output  
 
<img width="1109" height="797" alt="image" src="https://github.com/user-attachments/assets/9dc9a1c0-83f0-4f0d-9d94-62a1cd835d13" />


## Division alp 
```
org 100h
MOV AL,68H
MOV BL,18H
MUL BL
HLT
```

## Output  

<img width="1110" height="817" alt="image" src="https://github.com/user-attachments/assets/d02a444d-5b9d-4a04-89b6-fcb0b2314031" />


## Programs for logical  operations
## And of 8 bit numbers ALP
```
org 100h
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```
## Output 

<img width="1107" height="787" alt="image" src="https://github.com/user-attachments/assets/876d8bb9-a161-4587-b655-1644d6e5cef0" />

## OR of 8 bit numbers ALP
```
org 100h
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT
```
## Output  
<img width="1105" height="805" alt="image" src="https://github.com/user-attachments/assets/7e48f45b-5ea2-4222-aaa8-e3a99d3f77b2" />

## NOT of 8 bit number ALP
```
org 100h
MOV AL,65H
NOT AL
HLT
```

## Output  

<img width="1097" height="785" alt="image" src="https://github.com/user-attachments/assets/2d9fc9e5-6347-41c6-9ade-93b04cb5ab59" />

## NOR of 8 bit number ALP
```
org 100h
MOV AL,35H
MOV BL,66H
OR AL,BL
NOT AL
HLT
```
## Output  
<img width="1175" height="749" alt="image" src="https://github.com/user-attachments/assets/a24d5224-233d-490e-8d4a-7d5132b2a59e" />

## EX-OR of 8 bit number ALP
```
org 100h
MOV AL,10H
MOV BL,12H
XOR AL,BL
HLT
```
## Output 

<img width="1091" height="838" alt="image" src="https://github.com/user-attachments/assets/96a52d6d-b0bd-4d1a-b76d-3873e2f2dbd4" />

## EX-NOR of 8 bit number ALP
```
org 100h
MOV AL,65H
MOV BL,33H
XOR AL,BL 
NOT AL
HLT
```
## Output  
<img width="1309" height="850" alt="image" src="https://github.com/user-attachments/assets/eb1bd374-8e7e-438d-97b5-04965929c7db" />

## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








