[Back to Portfolio](./)

Single Cycle Processor Implementation
===============

-   **Class:Computer Archetecture (CSCI 220)** 
-   **Grade:TBA**
-   **Language(s):Verilog, x86 Assembly**
-   **Source Code Repository:** [features/mastering-markdown](https://github.com/brian2524/csci-330-spring-2020)  
    (Please [email me](mailto:BTHinkle@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

Written verilog modules that communicate to eachother as a whole. Reads in opcode to perform various tasks (ie. halt and loadWord).

## How to compiles / run the program
```bash
To compile, assemble, and run the simulation:
cd verilog/Single\ Cycle\ Processor/asm
./asm LW.asm LW.mc && cp LW.mc ../ && cd ..
iverilog *.v tests/test-SINGLECYCLEPROCESSORLW.v
make run
```
## 3. Additional Considerations

Project is not completely finished yet. Still need to implement rest of opcodes

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
