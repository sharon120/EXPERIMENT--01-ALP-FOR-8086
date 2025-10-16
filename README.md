# EXPERIMENT 01 ALP FOR 8086
```
Name : Sharon Harshini L M
Roll no : 212223040193
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


## Addition of 16 bit ALP 
```
MOV AX,48c6H
MOV BX,24e8H
ADD AX,BX
RET
```


## Output  
<img width="1919" height="1128" alt="Screenshot 2025-10-16 085424" src="https://github.com/user-attachments/assets/908bfedb-9db9-4a08-8b58-30629c612140" />


## Subtraction of 16 bit numbers  ALP 
 ```
MOV AX,89a7H
MOV BX,18f2H
SUB AX,BX
RET
```
## Output  
<img width="1919" height="1128" alt="image" src="https://github.com/user-attachments/assets/d8c3c03e-1c50-4a44-8c33-7ab166c9fdbd" />

## Multiplication of 16 bit numbers ALP 
```
org 100h
MOV AX,6d42H
MOV BX,387bH
MUL BX
RET
```
 ## Output  
<img width="1919" height="1134" alt="image" src="https://github.com/user-attachments/assets/047f656d-b6b1-4976-b092-855394a96681" />

## Division of 16 bit numbers ALP
```
MOV AX,5241H
MOV BX,27a1H
DIV BX
RET
```

## Output  
<img width="1919" height="1134" alt="image" src="https://github.com/user-attachments/assets/38af02d9-41f3-44b6-b047-4ac4b446b011" />


# AND of 16 bit numbers ALP
```
MOV AX,241fH
MOV BX,4372H
AND AX,BX
RET
```
# Output
<img width="1919" height="1132" alt="image" src="https://github.com/user-attachments/assets/2866f8b2-0433-4d1b-9bc0-1f34f1dd56bd" />


# OR of 16 bit numbers ALP
```
MOV AX,45d1H
MOV BX,662aH
OR AX,BX
RET
```
# Output
<img width="1919" height="1134" alt="image" src="https://github.com/user-attachments/assets/31ac442c-bc58-425e-8e99-dede8eeb44ee" />


# NOT of 16 bit numbers ALP
```
MOV AX,561cH
NOT AX
RET
```

# Output

<img width="1919" height="1123" alt="image" src="https://github.com/user-attachments/assets/eb188257-3594-44b8-8b0a-b6f306e29153" />

# XOR of 16 bit numbers ALP
```
MOV AX,98b2H
MOV BX,44d2H
XOR AX,BX
RET
```

# Output

<img width="1919" height="1128" alt="image" src="https://github.com/user-attachments/assets/35f9a198-63ef-4299-bd43-210113aea722" />



## Result :
The exeacution of ALP on fundamental arithmetic and logical operations is successfully completed.
 








