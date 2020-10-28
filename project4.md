[Back to Portfolio](./)

Processes Lab
===============

-   **Class: Operating Systems (CSCI 431)** 
-   **Grade: TBA**
-   **Language(s): C**
-   **Source Code Repository:** [csci-431-fall-2020](https://github.com/brian2524/csci-431-fall-2020)  
    (Please [email me](mailto:BTHinkle@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This lab demonstrates how you can communicate back and fourth between child and parent processes using shared memory.
This program takes in a value, N which represents the number of child processes to create. Each process generates a random number (0-9999). This program uses the shared memory to signal the parent process that the children are finished and tell it to determine the highest random number. The parent can then signal back, indicating which child process generated the largest value.

## How to compile / run the program
```
cd csci-431-fall-2020/lab03/src/
gcc lab03.c
./a.out <Input value>
```

![screenshot](images/lab03.PNG)
Fig 1. Running the program with an input of 3

[Back to Portfolio](./)
