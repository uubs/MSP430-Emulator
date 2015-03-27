MSP430-Emulator
===============

- Providing a software model of the MSP430 instruction set

  The first project goal is to provide a software model of the MSP430 
  instruction set, complete with an interactive debugger. 

  After that, other devices on the chip may be implemented providing a 
  simulated interface for serial communication, and general pin and 
  electronics testing with the 430 using WebGL to create a browser graphics 
  interface for virtual breadboarding. 

- TODO

  - Disassembly Coloring
  - Basic Clock Module Emulation

  - Instructions
    - SUB (Fix SUB.B overflow flag)
    - CMP (Fix CMP.B overflow flag)
    - DADD (BCD math)    
    - RETI (Return from Interrupt)