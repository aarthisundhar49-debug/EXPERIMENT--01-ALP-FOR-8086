# EXPERIMENT--01-ALP-FOR-8086
Name :Aarthi B
Roll no :212225230001
Date of experiment :7.10.2026





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
Org 100h
Mov ax, [1100h]
Mov bx, [1102h]
Add ax,bx
Mov [1200h],ax
ret
```


## Output  
 <img width="780" height="475" alt="image" src="https://github.com/user-attachments/assets/9b3cdd0c-cc7f-4177-a3be-36b0c7447d2b" />

## Subtraction   of 8 bit numbers  ALP 
```
Org 100h
Mov ax,[1100h]
Mov bx,[1102h]
Sub ax, bx
Mov [1200h], ax
ret
```
 
## Output  
<img width="762" height="433" alt="image" src="https://github.com/user-attachments/assets/8b5697cc-0c54-48e7-a9ba-a28a4a70016e" />

## Multiplication alp 
```
Org 100h
Mov ax, [1100h]
Mov bx, [1102h]
Mul bx
Mov [1200h], ax
Mov [1202h], dx
ret
```

 ## Output  
<img width="868" height="505" alt="image" src="https://github.com/user-attachments/assets/3bf08746-8be8-4029-a25c-6bde07fe4bd6" />


## Division alp 
```
Org 100h
Mov ax, [1100h]
Mov bx, [1102h]
div bx
Mov [1200h], ax
Mov [1202h], dx
ret
```

## Output  
<img width="872" height="527" alt="image" src="https://github.com/user-attachments/assets/04b98b92-48e3-4610-b95d-7c8ecc8f3ede" />

## AND of 8 bit numbers ALP
```
Org 100h
Mov bx, [1100h]
Mov cx, [1102h]
And bx,cx
ret
```

## Output
<img width="897" height="568" alt="image" src="https://github.com/user-attachments/assets/320dda52-b870-41a5-b847-2a7450602db8" />

## OR of 8 bit numbers ALP
```
Org 100h
Mov bx, [1100h]
Mov cx, [1102h]
OR bx,cx
ret
```

## Output
<img width="870" height="577" alt="image" src="https://github.com/user-attachments/assets/5c1fc162-17d8-4b2a-b5f8-2a16a7c5e6df" />

## NAND of 8 bit number ALP
```
Org 100h
Mov bx, [1100h]
Mov cx, [1102h]
AND bx, cx
NOT bx
ret
```
## Output
<img width="886" height="596" alt="image" src="https://github.com/user-attachments/assets/17c4b1c4-e345-4214-bec6-16d6c5102e5c" />

## NOR of 8 bit numbers ALP
```
Org 100h
Mov bx, [1100h]
Mov cx, [1102h]
OR bx,cx
NOT bx
ret
```

## Output
<img width="871" height="587" alt="image" src="https://github.com/user-attachments/assets/4eb24ed4-fec6-4391-a2a1-a8f73db4e376" />

## XOR of 8 bit number ALP
```
Org 100h
Mov bx, [1100h]
Mov cx, [1102h]
XOR bx,cx
ret
```

## Output 
<img width="868" height="580" alt="image" src="https://github.com/user-attachments/assets/33ee48e2-6352-4346-83b5-44a0947818a4" />

## EX-NOR of 8 bit number ALP
```
Org 100h
Mov bx, [1100h]
Mov cx, [1102h]
XOR bx,cx
NOT bx
ret
```

## Output
<img width="887" height="595" alt="image" src="https://github.com/user-attachments/assets/4dfbc05a-dd72-470b-82aa-59131b1c9a4e" />


## Result :
 The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








