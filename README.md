# Learning about MIPS
- Going to consider small subset of MIPS instruction not all of them so will do [[later]]

### Quick look at Mips32
- 32 gpr r0 - r31
- Has PC special purpose register also 32 bit - pints to the next instruction in memory to be fetched and executed.
- No flag register 
- limited set of addressing mode and only set of instruction that can access memory are load and store.
- We assume memory word size is 32 bits (word addressable)

### Instruction subset being consider 
- Load and store insturction
  ```
  LW R2,124(R8)
  SW R5,-10(R25)
  ```
- Arithmetic and logic instruction
  ```
  ADD R1,R2,R3
<<<<<<< HEAD
  ADD R1,R2,R0
=======
  ADD R1,R2,R0      // r1=r2+0
>>>>>>> 072a9d8 (something lets check)
  SUB R12,R10,R9
  AND R20,R1,R5
  OR R11,R5,R6
  OR R11,R5,R7
  MUL R5,R6,R7
  SLT R5,R11,R12
  ```
<<<<<<< HEAD
=======
- Arithmetic and logic instruction (Immediate operand)
>>>>>>> 072a9d8 (something lets check)
