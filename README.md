# EXPERIMENT--01-ALP-FOR-8086
## Name : AASHIKA JAIN . G
## Roll no : 212224110001
## Date of experiment : 02-02-2026

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
Mov AL,54H
MOV BL,60H
ADD AL,BL
HLT
```
## Output 

 <img width="1336" height="692" alt="image" src="https://github.com/user-attachments/assets/c4f11ef0-a5da-4eba-ab34-fa8965f8cc9d" />

## Subtraction   of 8 bit numbers  ALP 
```
org 100h
Mov AL,33H
MOV BL,11H
SUB AL,BL
HLT
```
 
## Output  
<img width="1410" height="717" alt="image" src="https://github.com/user-attachments/assets/4d7764bd-3c67-4509-81c3-7f3f8fbfd5ef" />

## Multiplication alp 
```
org 100h
MoV AL,84H
MOV BL,69H
MUL BL
HLT

```

 ## Output  
<img width="1358" height="786" alt="image" src="https://github.com/user-attachments/assets/6318cf94-0413-43e8-80de-72cb3b6b8367" />


## Division alp 
```
org 100h
MoV AL,66H
MOV BL,19H
MUL BL
HLT

```
## Output  
<img width="1452" height="688" alt="image" src="https://github.com/user-attachments/assets/09e65ac2-9447-4663-8217-6253dfc6f693" />

## Programs for logical operations
## And of 8 bit numbers ALP
```
org 100h
MOV AL,27H
MOV BL,68H
AND AL,BL
HLT

```
## Output

<img width="1486" height="676" alt="image" src="https://github.com/user-attachments/assets/d0bca05a-4286-4464-9566-10e87a933104" />

## OR of 8 bit numbers ALP
```
org 100h
MOV AL,37H
MOV BL,68H
OR AL,BL
HLT

```
## Output 
<img width="1331" height="654" alt="image" src="https://github.com/user-attachments/assets/4b066fff-35d9-4c27-974d-bc86d14591d2" />

## NOT of 8 bit numbers ALP
```
org 100h
MOV AL,65H
NOT AL
HLT

```
## Output

<img width="1526" height="816" alt="image" src="https://github.com/user-attachments/assets/8c4e31ea-d473-46f8-a0c3-098af593ce87" />

## NAND of 8 bit numbers ALP
```
org 100h
MOV AL,19H
MOV BL,08H
AND AL,BL
NOT AL
HLT

```
## Output
<img width="1323" height="766" alt="image" src="https://github.com/user-attachments/assets/c7aca71d-5d9a-4310-a326-87f07552c1ce" />

## NOR of 8 bit numbers ALP
```
org 100h
MOV AL,22H
MOV BL,29H
OR AL,BL
NOT AL
HLT

```
## Output

<img width="1554" height="703" alt="image" src="https://github.com/user-attachments/assets/b06fa03f-a9f7-4ecf-84b2-af7a1a0f99f7" />

## EX-OR of 8 bit numbers ALP
```
org 100h
MOV AL,12H
MOV BL,07H
XOR AL,BL
HLT

```
## Output
<img width="1456" height="899" alt="image" src="https://github.com/user-attachments/assets/74cb6e29-cde8-4fa0-8477-1171449568ec" />

## EX-NOR of 8 bit numbers ALP
```
org 100h
MOV AL,33H
MOV BL,67H
XOR AL,BL
NOT AL
HLT

```
## Output
<img width="1447" height="825" alt="image" src="https://github.com/user-attachments/assets/9f9f058b-f02d-4169-abd5-5d13ebe6171d" />

## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








