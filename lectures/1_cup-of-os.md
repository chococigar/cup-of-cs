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

In 1950's, computers could execute only one program at a time. (ex: with punched paper cards.)
But as computers got fast, there was a need to utilize resources better.

We needed things like: 
1. Batch programming
2. Multitasking
3. Time-sharing
4. Memory protection

Also there were different computers, so we needed some compatibility / editability in OS.

![history_of_os.png](../img/history_of_os.png)

* Please reference comments from [r/linux](https://www.reddit.com/r/linux/comments/kporah/i_made_a_simple_diagram_on_history_of_os_feel/) and [r/compsci](https://www.reddit.com/r/compsci/comments/kposlx/i_made_a_simple_diagram_on_history_of_os_feel/), where I posted this diagram and iteratively updated based on feedbacks.


### Mainframes and Microcomputers

### Multics and Unix
* Multics (1969)
    * Created by AT&T's Bell.
    * Most influential early time-sharing OS with multiprocessor systems. First major OS that is secure. Commercial success. But there was a drawback:
    > "It was over-ngineered... there was just too much of it." - Dennis
    > "Easily half of the code I was writing was error recovery code." - Ken 

* Unix
    * Created by Ken Thompson & Dennis Ritchie, frustrated in working in Multics.
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
        → This simplicity allowed Unix to run cheaper, making it available on simple hardware.
        
### Linux

### Apple (and Xerox)
* 1973: Xerox announces [Xerox Alto](https://history-computer.com/xerox-alto-complete-history-of-the-xerox-alto-computer/), the first OS based on GUI.
* 1979: Steve Jobs [visit Xerox PARC](https://web.stanford.edu/dept/SUL/sites/mac/parc.html), which inspired the potential of a GUI.
* 1983: Apple announces Apple Lisa, the first PC with GUI.
* 1984-2001: Apple release Classic MAC OS's for Macintosh PCs, which made GUI popular.
* 2001: Apple switches its OS to a BSD-based (Darwin OS, NEXTSTEP)
* 2007: Apple announces iOS, a mobile OS for iPhones based on Mac OS.

### Windows
* MS DOS/Disc Operating System (1981)
    * Created by Microsoft
    * One of the most popular OS for early home computers.  PC's started becoming cheaper as it became simpler, and a simple & light OS like MS DOS was suitable.
    * Lacked multitasking, memory protection
* Windows
    * Security (historically) criticized by customers
        * 1990s: lacked memory protection, Blue screen of death!


## References
* [Operating Systems: Crash Course Computer Science #18](https://youtu.be/26QPDBe-NB8)
