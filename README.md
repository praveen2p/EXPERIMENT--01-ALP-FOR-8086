#### Name : praveen.k
#### Roll no : 212223040152
# EXPERIMENT 01 - ALP FOR 8086
## Date of experiment :
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
org 100h

mov al,0a1h;

mov bx,12e1h;

add al,[bx];

ret


## Output
![Screenshot 2024-02-20 151844](https://github.com/praveen2p/EXPERIMENT--01-ALP-FOR-8086/assets/151658061/83451fba-ba75-4131-8bd0-9c0ab77aef52)

 
## Subtraction   of 8 bit numbers  ALP
org 100h

mov al,0a3h;

mov bx,0117h;

sub al,[bx];

mov [bx+1],al;

ret
 
## Output 
![Screenshot 2024-02-20 153442](https://github.com/praveen2p/EXPERIMENT--01-ALP-FOR-8086/assets/151658061/f6ce401b-85fe-4d73-a1d5-9b469a0e1a45)

## Multiplication alp
org 100h

mov al,0b2h;

mov bl,0a1h;

mul bl;

mov si,2314h;

mov [si],ax;

ret
 ## Output 
 ![Screenshot 2024-02-20 161000](https://github.com/praveen2p/EXPERIMENT--01-ALP-FOR-8086/assets/151658061/e20402c9-5c8a-4493-9065-dc297905cc71)



## Division alp 
org 100h

mov al,0e4h;

mov bl,0a5h;

div bl;

mov si,1723h;

mov [si],ax;

ret

## Output 
![Screenshot 2024-02-20 161459](https://github.com/praveen2p/EXPERIMENT--01-ALP-FOR-8086/assets/151658061/7595e08d-0ac3-4575-852c-011ead56ff43)

## AND alp
org 100h

mov al,0e4h;

mov bl,0a5h;

and al,bl;

mov si,2349h;

mov [si],ax;

ret
## Output
![Screenshot 2024-02-20 162242](https://github.com/praveen2p/EXPERIMENT--01-ALP-FOR-8086/assets/151658061/c9884fa6-90e7-4628-9e2f-0daaf9806d0e)

## OR alp
org 100h

mov al,0a1h;

mov bx,12e1h;

or al,[bx];

mov [bx+1],al;

ret


## Output
![Screenshot 2024-02-24 113936](https://github.com/praveen2p/EXPERIMENT--01-ALP-FOR-8086/assets/151658061/61419418-6104-479a-917b-209d9c27f1a3)

## NOT alp
org 100h

mov al,0a1h;

not al;

mov si,2314h;

mov [si],ax;

ret


## Output
![Screenshot 2024-02-25 110552](https://github.com/praveen2p/EXPERIMENT--01-ALP-FOR-8086/assets/151658061/86a7dd5c-db0c-4b21-8f99-bdf7122f5c2e)

## XOR alp
org 100h

mov al,0e1h;

mov bx,0a2h;

xor al,[bx];

mov si,2314h;

mov [si],ax;

ret



## Output
![Screenshot 2024-02-25 111128](https://github.com/praveen2p/EXPERIMENT--01-ALP-FOR-8086/assets/151658061/b821e235-495c-4d65-a6e5-aedcb49b5c9d)




## Result :The given fundamental arithmetic and logical operations are written and excutted using 8086.
 








