# Name : SUBASH M
# Reg no : 212223040210
# Date of experiment : 22-08-25
# EXPERIMENT 01 - ALP ON FUNDAMENTAL ARITHMETIC AND LOGICAL OPERATION USING 8086


## Aim:

To Write and execute ALP on fundamental arithmetic and logical operations

## Components required:

8086  emulator 

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

## Addition  of 16 bit ALP 
```
org 100h
mov ax,7c13h  
mov bx,5c2bh 
add ax,bx
ret
```

## Output  
<img width="1919" height="1199" alt="Screenshot 2025-08-18 140346" src="https://github.com/user-attachments/assets/5937b4d5-f9a2-4f7a-acac-2c1472a56390" />
 
## Subtraction  of 16 bit numbers  ALP 
```
org 100h
mov ax,3b23h  
mov bx,[2c9bh] 
sub ax,bx
ret
```

## Output  
<img width="1919" height="1136" alt="image" src="https://github.com/user-attachments/assets/21d404bb-7711-48f8-9e61-cb14c3a05f22" />


## Multiplication of 16 bit numbers ALP
```
org 100h
mov ax,81b2h  
mov bx,43h
mul bx
ret
```

## Output  
<img width="1919" height="1138" alt="image" src="https://github.com/user-attachments/assets/ec67a840-5268-4741-b9a6-1bf2b5fd63e4" />


## Division of 16 bit numbers ALP 
```
org 100h
mov ax,7c13h  
mov bx,[6d23h] 
div bx
ret
```

## Output  
<img width="1919" height="1199" alt="Screenshot 2025-08-18 144727" src="https://github.com/user-attachments/assets/835b60ee-385d-450e-86b0-18443930f835" />


## AND of 16 bit numbers  ALP 
```
org 100h
MOV ax,65cdH
MOV bx,43c8H
AND ax,bx
HLT
ret
```

## Output
<img width="1919" height="1135" alt="image" src="https://github.com/user-attachments/assets/d5a8c8e7-4e44-4537-ad3d-0bab9153f039" />


## OR of 16 bit numbers  ALP 
```
org 100h
MOV ax,29bdH
MOV bx,[41d8H]
OR ax,bx
HLT
ret
```

## Output
<img width="1919" height="1136" alt="image" src="https://github.com/user-attachments/assets/deb7babe-0aa4-401a-9e7a-223a3f3be4fa" />



## Not of 16 bit numbers  ALP 
```
org 100h
MOV ax,[65c6H]
NOT ax
HLT
ret
```

## Output
<img width="1919" height="1136" alt="image" src="https://github.com/user-attachments/assets/1d4c605d-b924-4669-ad64-574b4622dbb2" />


## XOR of 16 bit numbers  ALP 
```
org 100h
MOV bx,61c6H
MOV ax,[61c6H]
XOR ax,bx
HLT
ret
```

## Output
<img width="1919" height="1139" alt="image" src="https://github.com/user-attachments/assets/2587961c-5676-4f5d-94f3-8b7bd62b4ce2" />


## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








