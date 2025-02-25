# EXPERIMENT--01-ALP-FOR-8086

Name : 

Roll no :

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
mov al,53h;
mov bl,24h;
add al,bl;
hlt
```
## Output 

![Screenshot 2024-08-24 134544](https://github.com/user-attachments/assets/d57dc058-c074-46fe-91ff-0797c466b68d)
 
## Subtraction   of 8 bit numbers  ALP
```
mov al,53h;
mov bl,24h;
sub al,bl;
hlt
``` 
## Output

![Screenshot 2024-08-24 135652](https://github.com/user-attachments/assets/a47005e2-22d7-4130-970f-fdad73f87923)

## Multiplication alp
```
mov al,53h;
mov bl,24h;
mul bl;
hlt
```
 ## Output  
 
![Screenshot 2024-08-24 140308](https://github.com/user-attachments/assets/4244cb51-8e7e-4ff2-bca6-12ba8eda1965)

## Division alp 
```
mov al,53h;
mov bl,24h;
div bl;
hlt
```
## Output  

![Screenshot 2024-08-24 140953](https://github.com/user-attachments/assets/1c541adc-bed5-44cb-abbc-f51a6b391f3d)

## And of 8 bit numbers ALP
```
MOV AL,53H
MOV BL,24H
AND AL,BL
hlt
```
 ## Output  
 
![Screenshot 2024-08-24 141115](https://github.com/user-attachments/assets/53bd7224-b244-4d89-8936-c64d7869d236)

## OR of 8 bit numbers ALP
```
MOV AL,53H
MOV BL,24H
OR AL,BL
HLT
```
 ## Output  
 ![Screenshot 2024-08-24 141219](https://github.com/user-attachments/assets/9efa002a-1271-46b2-aece-3afb5b1809c0)

## NOT of 8 bit number ALP
```
MOV AL,53H
NOT AL
HLT
```
 ## Output  
 
![Screenshot 2024-08-24 141319](https://github.com/user-attachments/assets/7e3a20d4-0525-4b44-8c58-8fd392da3ddc)

## XOR of 8 bit number ALP
```
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
```
 ## Output  
 ![Screenshot 2024-08-24 141559](https://github.com/user-attachments/assets/3dd2df90-afb3-4add-88e6-f51cda800527)
 
## Result :
Thus, a program is executed on ALP for the fundamental arithmetic and logical operations. 








