# EXPERIMENT--01-ALP-FOR-8086
Name : ANUMITHA.M.R

Roll no : 212223040018

Date of experiment :16/08/2024





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
 MOV al,11h;
 MOV bl,20h;
 ADD al,bl;
 MOV [6379h],al;
 ret
 ```


## Output  

![Screenshot 2024-08-19 132424](https://github.com/user-attachments/assets/8ff95ca6-7bb9-4ab4-961e-d5ffba458471)

 
## Subtraction   of 8 bit numbers  ALP 
```
 org 100h
 MOV al,20h;
 MOV bl,[8778h];
 SUB bl,al;
 MOV [8798h],bl;
 ret
 ```
## Output

![Screenshot 2024-08-19 132446](https://github.com/user-attachments/assets/4428bed5-9aac-4b60-b363-237bf7daef2b)


## Multiplication alp 
```
 org 100h
 MOV al,13h;
 MOV bl,2h;
 MUL bl;
 MOV [6063h],bl;
 ret
 ```
 ## Output  

![Screenshot 2024-08-19 132500](https://github.com/user-attachments/assets/b139cf56-f666-474e-8287-9ac3571e9167)


## Division alp 
```
 org 100h
 MOV al,26h;
 MOV bl,[2369h];
 DIV bl;
 MOV [2399h],al;
 ret
 ```
## Output  

![Screenshot 2024-08-19 132514](https://github.com/user-attachments/assets/d5723e5b-6cae-4fb1-81c3-f344f167a4e9)

## Programs for Logical Operations

## OR Operation
```
 org 100H  
 MOV SI,0532H;
 MOV AX,0A32H;
 MOV BX,0B13H;
 OR AX,BX;
 ret
```

## Output
![Screenshot 2024-08-19 132553](https://github.com/user-attachments/assets/c3c15494-3352-4430-9c14-34bc491830f2)

## AND Operation
```
 org 100H  
MOV [SI],AX;
 MOV AX,0A32H;
 MOV BX,0B13H;
 AND AX,BX; 
ret
```
## Output

![Screenshot 2024-08-19 132610](https://github.com/user-attachments/assets/b2f7438f-8b0c-4134-abb0-1d50d8259019)


## XOR Operation
```
org 100H  
MOV [SI+2],AX;
 MOV AX,0A32H;
 MOV BX,0B13H; 
XOR AX,BX;  
ret
```

## Output

![Screenshot 2024-08-19 132628](https://github.com/user-attachments/assets/411a03fc-6dfb-4938-89d1-8a7601b840b9)

## NOT Operation

```
 org 100H  
 MOV [SI+4],AX;
 MOV AX,0A32H;
 NOT AX; 
 MOV [SI+6],AX;
 ret
```

## Output

![Screenshot 2024-08-19 132643](https://github.com/user-attachments/assets/cc9ae1c2-0a23-4637-b5eb-1256dfad190e)

## Result :
  Thus, APL for fundamental arithmetic and logical operations are executed successfully.
 








