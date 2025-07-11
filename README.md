## About Me
```
silas@hobbit:/tmp/tmp.sMMKH3yomH$ cat github_profile.s
.intel_syntax noprefix

.section .text
    .global _start

_start:
    call greet_visitor
    
    mov rdi, 0 
    mov rax, 60 
    syscall

greet_visitor:
    mov rdi, 1 
    lea rsi, MESSAGE 
    mov rdx, MESSAGE_LENGTH
    
    mov rax, 1 
    syscall
    
    mov rax, 0
    ret

.section .data
    MESSAGE:
        .string "Hey 👋, I'm Silas! \n\nA Computer Science student from the United States of America with a passion for technology and problem solving.\n"
    MESSAGE_LENGTH:
        .int 135
silas@hobbit:/tmp/tmp.sMMKH3yomH$ as -o github_profile.o github_profile.s; ld -o github_profile github_profile.o
silas@hobbit:/tmp/tmp.sMMKH3yomH$ ./github_profile
Hey 👋, I'm Silas! 

A Computer Science student from the United States of America with a passion for technology and problem solving.
```

## Languages and Development Tools
* Python
* Java
* x86-64 Assembly
* PHP
* HTML
* Bash
* PowerShell
* Git
* Visual Studio Code
* NetBeans
* Vim

## Operating Systems
* Linux
* Windows

## Interests
* Information Security
* Artificial Intelligence
* Computer Engineering
* Open-Source Software
* Fantasy Books
* Environmental Protection and Sustainability

## Get In Touch
* :mailbox: [Email](mailto:formaljek14@gmail.com)
* :speech_balloon: [LinkedIn](https://linkedin.com/in/silas-accles)
