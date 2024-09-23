# EXPERIMENT--01-ALP-FOR-8086
```
Name : DHARSHINI S
Roll no : 212223110010
Date of experiment : 12-08-2024

```



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
mov AL,53H;
mov BL,24H;
Add AL,BL;
HLT;
```
## Output  
![1](https://github.com/user-attachments/assets/83cbb66c-6e4f-4685-bb1a-16ed3c0a4c85)
 
## Subtraction   of 8 bit numbers  ALP 
```
mov AL,53H;
mov BL,24H;
sub AL,BL;
HLT;
```
## Output 
![2](https://github.com/user-attachments/assets/e3a0f60c-23d4-4731-b4b4-be3b2df3eff1)

## Multiplication alp 
```
mov AL,53H;
mov BL,24H;
mul AL,BL;
HLT;
```
 ## Output  
![3](https://github.com/user-attachments/assets/7c8238cc-6e1a-4ada-b670-b5eb8e45fccf)


## Division alp 
```
mov AL,53H;
mov BL,24H;
Div AL,BL;
HLT;
```

## Output  
![4](https://github.com/user-attachments/assets/f44c76d9-7e4d-4062-abba-d660ac2dea36)

## Logical AND
```
mov AL,53H;
mov BL,24H;
AND AL,BL;
HLT;
```
## Output
![5](https://github.com/user-attachments/assets/3cf16646-01a1-49f9-86b4-f2685bfb895d)
## Logical OR
```
mov AL,53H;
mov BL,24H;
OR AL,BL;
HLT;
```
## Output
![6](https://github.com/user-attachments/assets/0c261b3b-9f83-4463-b84e-70b5004e482f)

## Logical NOT
```
mov AL,53H;
not AL;
HLT;
```
## Output
![8](https://github.com/user-attachments/assets/944583c0-dd45-4593-9c22-199ce6f66013)

## Logical XOR
```
mov AL,53H;
mov BL,24H;
XOR AL,BL;
HLT;
```
## Output
![9](https://github.com/user-attachments/assets/52e976e2-f379-407c-b0df-dedd8080c276)

## Result :
 Thus the program for arithmetic operations and logical operations are completed.








