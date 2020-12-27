# ☕✨cup-of-OS✨
Easy sips of basic concepts of OS #tldr #eli5

Presentation [here](https://docs.google.com/presentation/d/1ya2-NfS2mJQ-V4qFdMmBMXSjMTHaSbZGE-x8RvJ-wiM/edit?usp=sharing) on 12/27/2020 by [chococigar@](https://github.com/chococigar)

// Please PR on any info that needs correction or addition.

## what we'll cover
1. History of OS - why we have it in the first place
    - Unix variants,  MS DOS, Posix, etc
    - Important people and important companies
2. Components of OS and its key philosophy
    - kernels, ABIs, abstraction, etc
3. Q&A
    - Answering previously asked questions

## History of OS

### In the beginning...
There was just one job.

But computers got fast, so we needed to utilize resources better.

We needed things like: 
1. Batch programming
2. Multitasking
3. Time-sharing
4. Memory protection

Also there were different computers, so we needed some compatibility / editability in OS.

### Multics and Unix
* Multics
    * Created by AT&T's Bell.
    * One of the earliest multiprocessor systems. First major OS that is secure. Commercial success. But there was a drawback:
    > "Overengineered... half of the code was error recovery." - Dennis, working in Multics

* Unix
    * Ken Thompson & Dennis Ritchie, frustrated in working in Multics, created Unix.
        * Ken Thompson: 
            * Made Go lang
            * Made UTF8
        * Dennis Ritchie: 
            * Made C
    * UNICS (Uniplexed Information and Computing Service)
    * Two components
        * Core (kernel❤️): memory managing, multitasking
        * Libraries / programs
    * If it crashes, we’ll just show kernel panic & tell user to reboot ¯\_(ツ)_/¯
        → Unix runs cheaper, available on simple hardware.
        
### Windows
* Windows
    * Created by Microsoft
    * Security (historically) criticized by customers
        * 1990s: lacked memory protection, Blue screen of death!




## History of OS

## References
