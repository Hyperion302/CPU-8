# CPU-8
An 8 Bit CPU with a RISC architecture built and simulated on Logism
# Instruction Set
This CPU uses a simple instruction set consisting of add, subtract, memory, and jump instructions.  It is important
to note that the final register in the register array (register 11) is considered the out port.
| Handle  | Opcode | Operator | Params |
|---------|--------|----------|--------|
| ADDI    | 01     | 00       |        |
| ADD     | 01     | 01       |        |
| SUB     | 01     | 11       |        |
| SUBI    | 01     | 10       |        |
| READI   | 10     | 01       |        |
| READ    | 10     | 00       |        |
| WRITEI  | 10     | 11       |        |
| WRITE   | 10     | 10       |        |
| JMPABSI | 11     | 00       |        |
| JMP     | 11     | 01       |        |
| JMPZ    | 11     | 10       |        |
| JMPNZ   | 11     | 11       |        |
