# Virtual Machine - Custom Assembly Language
A small custom instruction set bytecode compiled language with a virtual machine.  
Made in qb64  

## Registers:
* General Purpose Registers: RA, RB
* Mouse Registers: RC, RD
* String Pointers: RE, RF
* Instruction Pointers: RG
* Key Pointers: RH

## Stack:
Different stacks for every type of registers.  

## Flags:
* Zero
* Carry
* Equal
* Greater
* Lesser
* Mousebutton {1, 2, 3}
* Mouse Scroll {Up, Down}

## Instructions:
For more information: check [instructions.txt](https://github.com/AadityaParashar0901/vm/blob/master/instructions.txt)  
Arithmetic instructions, different by their arguments  
Movement instructions, different by their arguments  
Flag Set / Clear instructions  
Halt, System instruction  
Mouse handling instructions  
Compare instructions  
Jump, call instructions  
Time instruction  
Stack instructions  
Cursor management instruction  
String printing instruction  
Load and Store instructions  
Clear screen instruction  
Input-Output instructions  
Graphics pixel management instructions  
