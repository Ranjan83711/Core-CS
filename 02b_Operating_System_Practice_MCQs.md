# Operating System: Practice MCQs (200 questions)

**Bihar STET Paper 2 (Computer Science)**

There are 10 topics with 20 questions each. Attempt a topic, then open its **Answer key**. Target: 17/20 or better.

Topics G (Virtual Memory), E (Deadlock) and I (Disk scheduling) haven't been asked yet, but they are core syllabus. The numerical questions here are for safety.

---

## A. OS Basics & Types

**1.** An operating system acts as an interface between:
(A) the user and the hardware  (B) the CPU and memory  (C) the compiler and the linker  (D) two users

**2.** Which core part of the OS always stays in main memory?
(A) Shell  (B) Kernel  (C) Compiler  (D) BIOS

**3.** In UNIX, the program that reads and interprets user commands is the:
(A) kernel  (B) loader  (C) shell  (D) linker

**4.** The OS kernel runs in:
(A) user mode  (B) debug mode  (C) safe mode  (D) kernel (supervisor) mode

**5.** In most systems, a mode bit of 0 means:
(A) kernel mode  (B) user mode  (C) idle mode  (D) sleep mode

**6.** A system call is:
(A) a hardware interrupt  (B) a compiler error  (C) a program's request to the OS for a service  (D) any library function

**7.** The program that loads the OS into memory at start-up is the:
(A) linker  (B) bootstrap loader  (C) compiler  (D) assembler

**8.** The bootstrap program is usually stored in:
(A) RAM  (B) ROM/firmware  (C) the disk cache  (D) a CPU register

**9.** A batch operating system:
(A) groups jobs with similar needs and runs them without user interaction  (B) is highly interactive  (C) is a real-time system  (D) is a distributed system

**10.** A time-sharing OS works by:
(A) running one job at a time  (B) not using the CPU  (C) running batch jobs only  (D) giving each user a small slice of CPU time in turn

**11.** The main aim of multiprogramming is to:
(A) increase CPU utilisation  (B) reduce memory size  (C) increase I/O time  (D) support only one user

**12.** In which type of OS is missing a deadline treated as a system failure?
(A) Soft real-time  (B) Hard real-time  (C) Batch  (D) Time-sharing

**13.** Which is an example of a hard real-time system?
(A) Video streaming  (B) Word processing  (C) A car's airbag controller  (D) E-mail

**14.** A distributed OS:
(A) makes a group of independent computers appear as one system  (B) manages a single CPU only  (C) manages printers only  (D) runs batch jobs only

**15.** Multiprocessing means a system has:
(A) more than one user  (B) more than one CPU/processor  (C) more than one program in memory  (D) more than one disk

**16.** Which of these is **not** an operating system?
(A) Linux  (B) Windows  (C) Oracle Database  (D) Android

**17.** Who created the Linux kernel?
(A) Dennis Ritchie  (B) Linus Torvalds  (C) Ken Thompson  (D) Bill Gates

**18.** UNIX was developed at:
(A) Microsoft  (B) IBM  (C) Apple  (D) AT&T Bell Labs

**19.** MS-DOS is a:
(A) single-user, single-tasking, command-line OS  (B) multi-user GUI OS  (C) real-time OS  (D) distributed OS

**20.** Android is built on the:
(A) Windows kernel  (B) DOS kernel  (C) Linux kernel  (D) Symbian kernel

<details><summary><b>Answer key: A</b></summary>

| Q | Ans | Note |
|---|---|---|
| 1 | A | It is also a resource manager |
| 2 | B | |
| 3 | C | e.g. bash |
| 4 | D | Also called privileged mode (PYQ 2025) |
| 5 | A | 1 = user mode |
| 6 | C | e.g. fork(), read(), write() |
| 7 | B | |
| 8 | B | |
| 9 | A | |
| 10 | D | Uses a time quantum |
| 11 | A | The CPU always has a job to run |
| 12 | B | Soft real-time = occasional misses are tolerated |
| 13 | C | |
| 14 | A | |
| 15 | B | |
| 16 | C | It is a DBMS |
| 17 | B | 1991 |
| 18 | D | Ken Thompson & Dennis Ritchie, 1969 |
| 19 | A | DOS = Disk Operating System (PYQ 2019) |
| 20 | C | Android is an OS (PYQ 2020) |
</details>

---

## B. Process & Threads

**1.** A process is:
(A) a program in execution  (B) a program stored on disk  (C) a file  (D) a device

**2.** Information about a process (state, PC, registers…) is kept in the:
(A) FAT  (B) inode  (C) PCB  (D) page table

**3.** A process moves from *running* to *waiting* when:
(A) it requests I/O  (B) its time slice expires  (C) it is created  (D) it terminates

**4.** A process moves from *running* to *ready* when:
(A) it requests I/O  (B) its time quantum expires or an interrupt occurs  (C) its I/O completes  (D) it exits

**5.** A process moves from *waiting* to *ready* when:
(A) the dispatcher selects it  (B) a time-out occurs  (C) it exits  (D) the event or I/O it was waiting for completes

**6.** A context switch involves:
(A) formatting the disk  (B) saving the state of the current process and loading the state of the next  (C) compiling a program  (D) switching to another OS

**7.** Context-switch time is:
(A) pure overhead  (B) productive work  (C) always zero  (D) something that increases throughput

**8.** A thread is:
(A) a heavyweight process  (B) a file  (C) a lightweight process (basic unit of CPU use)  (D) a device driver

**9.** Threads of the same process share:
(A) code, data and open files  (B) the stack  (C) registers  (D) the program counter

**10.** Each thread has its own:
(A) code section  (B) data section  (C) stack and registers  (D) open files

**11.** A process that creates another process is called the:
(A) child  (B) parent  (C) orphan  (D) zombie

**12.** A zombie process is one that:
(A) has finished, but its entry is still in the process table because the parent hasn't collected its status  (B) is still running  (C) has lost its parent  (D) is swapped out

**13.** An orphan process is one whose:
(A) child has terminated  (B) memory is swapped out  (C) I/O is blocked  (D) parent has terminated while it is still running

**14.** Which UNIX system call creates a new process?
(A) fork()  (B) exec()  (C) create()  (D) spawn()

**15.** The two basic models of IPC are:
(A) paging and swapping  (B) shared memory and message passing  (C) segmentation and paging  (D) spooling and buffering

**16.** A pipe is used for:
(A) inter-process communication  (B) memory allocation  (C) disk scheduling  (D) booting

**17.** The long-term (job) scheduler controls:
(A) the degree of multiprogramming  (B) which ready process gets the CPU next  (C) swapping  (D) I/O devices

**18.** The short-term (CPU) scheduler:
(A) picks jobs from the job pool  (B) picks a ready process to run on the CPU  (C) swaps processes out  (D) manages I/O

**19.** The medium-term scheduler handles:
(A) CPU dispatching  (B) job admission  (C) swapping (suspending and resuming processes)  (D) I/O requests

**20.** The dispatcher:
(A) gives CPU control to the process chosen by the short-term scheduler  (B) creates processes  (C) allocates memory  (D) manages files

<details><summary><b>Answer key: B</b></summary>

| Q | Ans | Note |
|---|---|---|
| 1 | A | A program is passive, a process is active |
| 2 | C | Process Control Block |
| 3 | A | |
| 4 | B | |
| 5 | D | |
| 6 | B | Enables multitasking (PYQ 2025) |
| 7 | A | No useful work happens during the switch |
| 8 | C | |
| 9 | A | |
| 10 | C | Plus its own program counter |
| 11 | B | |
| 12 | A | |
| 13 | D | Adopted by init/systemd |
| 14 | A | exec() replaces the process image |
| 15 | B | IPC = exchange of information and synchronization (PYQ 2025) |
| 16 | A | |
| 17 | A | |
| 18 | B | Runs most frequently |
| 19 | C | |
| 20 | A | Its delay is the *dispatch latency* |
</details>

---

## C. CPU Scheduling

**1.** FCFS scheduling is:
(A) non-preemptive  (B) preemptive  (C) priority-based  (D) random

**2.** Round Robin scheduling is based on a:
(A) priority only  (B) time quantum  (C) shortest job  (D) deadline

**3.** Which algorithm gives the minimum average waiting time?
(A) FCFS  (B) SJF  (C) Round Robin  (D) Priority

**4.** The convoy effect is seen in:
(A) FCFS  (B) Round Robin  (C) SRTF  (D) Multilevel queue

**5.** Which algorithm can cause starvation?
(A) FCFS  (B) Round Robin  (C) Priority scheduling  (D) None of these

**6.** The usual solution to starvation is:
(A) paging  (B) swapping  (C) thrashing  (D) aging

**7.** SRTF is the preemptive version of:
(A) FCFS  (B) SJF  (C) Round Robin  (D) Priority

**8.** If the time quantum in Round Robin is very large, it behaves like:
(A) FCFS  (B) SJF  (C) Priority  (D) LIFO

**9.** Turnaround time equals:
(A) burst time − arrival time  (B) waiting time + arrival time  (C) completion time − arrival time  (D) completion time − burst time

**10.** Waiting time equals:
(A) turnaround time − burst time  (B) completion time − arrival time  (C) burst time − arrival time  (D) arrival time − burst time

**11.** P1 (burst 24), P2 (3) and P3 (3) all arrive at time 0 in that order. What is the average waiting time under FCFS?
(A) 3  (B) 17  (C) 13  (D) 27

**12.** For the same processes, what is the average waiting time under SJF?
(A) 17  (B) 6  (C) 3  (D) 9

**13.** Throughput is the:
(A) number of processes completed per unit time  (B) time to complete one process  (C) time spent waiting  (D) time to first response

**14.** Response time is the time from submitting a request until:
(A) the process finishes  (B) it starts waiting  (C) completion  (D) the first response is produced

**15.** Scheduling in which a running process can be interrupted is called:
(A) preemptive  (B) non-preemptive  (C) batch  (D) FCFS

**16.** In multilevel queue scheduling:
(A) there is a single ready queue  (B) the ready queue is split into several separate queues  (C) there are no priorities  (D) only Round Robin is used

**17.** A multilevel feedback queue allows processes to:
(A) move between queues  (B) stay in fixed queues  (C) avoid preemption  (D) share one queue

**18.** Rate-Monotonic scheduling gives higher priority to tasks with a:
(A) longer period  (B) larger burst  (C) shorter period  (D) later arrival

**19.** In EDF scheduling, the highest priority goes to the task with the:
(A) earliest deadline  (B) shortest burst  (C) longest burst  (D) earliest arrival

**20.** The main practical difficulty with SJF is that:
(A) it is too simple  (B) it causes the convoy effect  (C) it never starves processes  (D) the length of the next CPU burst is hard to know in advance

<details><summary><b>Answer key: C</b></summary>

| Q | Ans | Note |
|---|---|---|
| 1 | A | |
| 2 | B | |
| 3 | B | Provably optimal |
| 4 | A | Short jobs wait behind a long one |
| 5 | C | SJF can starve processes too |
| 6 | D | Gradually raise the priority of waiting processes |
| 7 | B | Shortest Remaining Time First |
| 8 | A | |
| 9 | C | TAT = CT − AT |
| 10 | A | WT = TAT − BT |
| 11 | B | Waits 0, 24, 27 → 51/3 = 17 |
| 12 | C | Order P2, P3, P1 → waits 0, 3, 6 → 3 |
| 13 | A | |
| 14 | D | |
| 15 | A | |
| 16 | B | e.g. foreground (RR) and background (FCFS) |
| 17 | A | |
| 18 | C | Static priority |
| 19 | A | Dynamic priority. EDF and SCAN-EDF suit multimedia (PYQ 2025). |
| 20 | D | It is usually predicted by exponential averaging |
</details>

---

## D. Process Synchronization

**1.** A critical section is:
(A) code that accesses shared resources  (B) the OS kernel  (C) boot code  (D) an interrupt

**2.** What three requirements must a critical-section solution meet?
(A) paging, segmentation, swapping  (B) mutual exclusion, progress, bounded waiting  (C) FCFS, SJF, RR  (D) none of these

**3.** Who introduced semaphores?
(A) Dijkstra  (B) Hoare  (C) Turing  (D) Torvalds

**4.** What are the two operations on a semaphore?
(A) read and write  (B) fork and exec  (C) wait (P) and signal (V)  (D) open and close

**5.** A binary semaphore can take the values:
(A) any integer  (B) 0 and 1  (C) negative values only  (D) 0 to 10

**6.** A counting semaphore is used to control access to:
(A) a resource with a single instance only  (B) memory  (C) files  (D) a resource with multiple instances

**7.** A mutex is basically:
(A) a counting semaphore  (B) a page  (C) a binary lock for mutual exclusion  (D) a file

**8.** A race condition occurs when:
(A) a disk fails  (B) the result depends on the timing/order in which processes access shared data  (C) the CPU is idle  (D) two users log in

**9.** A semaphore that busy-waits is called a:
(A) mutex  (B) spinlock  (C) monitor  (D) barrier

**10.** A monitor is a:
(A) hardware device  (B) scheduler  (C) high-level synchronization construct (abstract data type)  (D) file

**11.** Monitors were proposed by:
(A) Hoare and Brinch Hansen  (B) Peterson  (C) Knuth  (D) Turing

**12.** What are the two operations on condition variables inside a monitor?
(A) P and V  (B) fork  (C) wait() and signal()  (D) lock

**13.** Peterson's solution works for:
(A) n processes  (B) deadlock detection  (C) paging  (D) two processes

**14.** The producer–consumer problem is also called the:
(A) bounded-buffer problem  (B) dining philosophers problem  (C) readers–writers problem  (D) sleeping barber problem

**15.** The dining philosophers problem illustrates:
(A) paging  (B) deadlock and starvation among processes sharing resources  (C) file systems  (D) booting

**16.** With 5 philosophers, how many chopsticks are there?
(A) 10  (B) 5  (C) 4  (D) 6

**17.** In the readers–writers problem:
(A) only one reader can read at a time  (B) writers can share access  (C) many readers can read together, but a writer needs exclusive access  (D) none of these

**18.** Which hardware instruction is used for synchronization?
(A) Test-and-Set  (B) ADD  (C) MOV  (D) JMP

**19.** The sleeping barber problem is a:
(A) disk-scheduling problem  (B) memory problem  (C) networking problem  (D) classic synchronization problem

**20.** In producer–consumer, the consumer must wait when the buffer is:
(A) full  (B) half-full  (C) empty  (D) any of these

<details><summary><b>Answer key: D</b></summary>

| Q | Ans | Note |
|---|---|---|
| 1 | A | |
| 2 | B | |
| 3 | A | 1965 |
| 4 | C | |
| 5 | B | |
| 6 | D | |
| 7 | C | |
| 8 | B | |
| 9 | B | |
| 10 | C | Used for mutual exclusion and synchronization (PYQ 2025) |
| 11 | A | If only Dijkstra is offered, pick Dijkstra (PYQ 2025) |
| 12 | C | |
| 13 | D | |
| 14 | A | Shared buffer (PYQ 2025) |
| 15 | B | About mutual exclusion (PYQ 2025) |
| 16 | B | |
| 17 | C | |
| 18 | A | Also Swap / Compare-and-Swap |
| 19 | D | |
| 20 | C | The producer waits when it is full |
</details>

---

## E. Deadlocks

**1.** Which is **not** one of the necessary conditions for deadlock?
(A) Mutual exclusion  (B) Hold and wait  (C) Preemption  (D) Circular wait

**2.** How many necessary (Coffman) conditions for deadlock are there?
(A) 2  (B) 3  (C) 4  (D) 5

**3.** The Banker's algorithm is used for deadlock:
(A) avoidance  (B) prevention  (C) detection  (D) recovery

**4.** Who proposed the Banker's algorithm?
(A) Knuth  (B) Dijkstra  (C) Hoare  (D) Peterson

**5.** A safe state means:
(A) resources can be given to every process in some order without deadlock  (B) a deadlock exists  (C) no process is running  (D) the system is unsafe

**6.** In a resource-allocation graph where each resource has one instance, a cycle means:
(A) no deadlock  (B) a possible deadlock  (C) starvation  (D) a definite deadlock

**7.** If resources have several instances, a cycle in the graph means:
(A) a definite deadlock  (B) no deadlock  (C) a deadlock may or may not exist  (D) an error

**8.** Numbering resources and requesting them only in increasing order prevents:
(A) circular wait  (B) mutual exclusion  (C) preemption  (D) hold and wait

**9.** Making a process request all its resources at once prevents:
(A) circular wait  (B) hold and wait  (C) mutual exclusion  (D) none of these

**10.** The "ostrich algorithm" means:
(A) ignoring the deadlock problem  (B) detecting deadlock  (C) preventing deadlock  (D) avoiding deadlock

**11.** A wait-for graph is used for:
(A) paging  (B) scheduling  (C) file management  (D) deadlock detection

**12.** Recovery from deadlock is done by:
(A) terminating processes or preempting resources  (B) adding RAM  (C) rebooting only  (D) recompiling

**13.** Starvation means:
(A) all processes are blocked  (B) the same thing as deadlock  (C) a process waits indefinitely while others make progress  (D) none of these

**14.** Livelock means processes:
(A) keep changing state but make no progress  (B) are in deadlock  (C) are paging  (D) none of these

**15.** If a safe sequence exists, the state is:
(A) unsafe  (B) safe  (C) deadlocked  (D) starved

**16.** An unsafe state:
(A) may lead to deadlock  (B) always means deadlock  (C) never leads to deadlock  (D) is the same as safe

**17.** Three processes each need 2 units of one resource type. What is the minimum number of units that guarantees no deadlock?
(A) 3  (B) 4  (C) 5  (D) 6

**18.** In the Banker's algorithm, the Need matrix equals:
(A) Allocation − Max  (B) Available − Max  (C) Max − Allocation  (D) Max + Allocation

**19.** Allowing resources to be taken away from a process breaks which condition?
(A) Mutual exclusion  (B) Circular wait  (C) Hold and wait  (D) No preemption

**20.** Mutual exclusion cannot be removed for:
(A) a printer (non-sharable)  (B) read-only files  (C) the system clock  (D) none of these

<details><summary><b>Answer key: E</b></summary>

| Q | Ans | Note |
|---|---|---|
| 1 | C | The condition is *no* preemption |
| 2 | C | Mutual exclusion, hold & wait, no preemption, circular wait |
| 3 | A | |
| 4 | B | |
| 5 | A | |
| 6 | D | |
| 7 | C | |
| 8 | A | |
| 9 | B | |
| 10 | A | Used by Windows/UNIX |
| 11 | D | Single-instance resources |
| 12 | A | |
| 13 | C | |
| 14 | A | |
| 15 | B | |
| 16 | A | |
| 17 | B | n(k − 1) + 1 = 3 × 1 + 1 = 4 |
| 18 | C | |
| 19 | D | |
| 20 | A | |
</details>

---

## F. Memory Management

**1.** Main memory is also called:
(A) primary memory  (B) secondary memory  (C) tertiary memory  (D) cache only

**2.** The MMU maps:
(A) physical addresses to disk  (B) logical (virtual) addresses to physical addresses  (C) IP addresses to MAC addresses  (D) file names to blocks

**3.** The address generated by the CPU is the:
(A) logical address  (B) physical address  (C) MAC address  (D) port address

**4.** In paging, physical memory is divided into:
(A) pages  (B) segments  (C) frames  (D) variable-sized blocks

**5.** Paging eliminates:
(A) external fragmentation  (B) internal fragmentation  (C) both  (D) neither

**6.** Paging can still suffer from:
(A) external fragmentation  (B) internal fragmentation  (C) no fragmentation  (D) both

**7.** Segmentation suffers from:
(A) internal fragmentation  (B) no fragmentation  (C) external fragmentation  (D) thrashing

**8.** A page table translates:
(A) a logical page number into a physical frame number  (B) frames to disk blocks  (C) file names  (D) IP addresses

**9.** The TLB is:
(A) a disk  (B) a register file  (C) a page frame  (D) a fast associative cache of page-table entries

**10.** With a 32-bit logical address and a 4 KB page size, how many bits are used for the page offset?
(A) 12  (B) 20  (C) 10  (D) 32

**11.** In the same system, how many pages are there?
(A) 2¹²  (B) 2²⁰  (C) 2³²  (D) 2¹⁰

**12.** First fit allocates:
(A) the first hole that is big enough  (B) the smallest hole  (C) the largest hole  (D) the last hole

**13.** Best fit allocates:
(A) the largest hole  (B) the first hole  (C) the smallest hole that is big enough  (D) a random hole

**14.** Worst fit allocates:
(A) the smallest hole  (B) the first hole  (C) the last hole  (D) the largest hole

**15.** Compaction solves:
(A) external fragmentation  (B) internal fragmentation  (C) thrashing  (D) deadlock

**16.** Fixed (static) partitioning causes:
(A) external fragmentation only  (B) internal fragmentation  (C) no fragmentation  (D) thrashing

**17.** Overlays allow:
(A) programs larger than memory to run by loading only the parts needed  (B) memory sharing  (C) IPC  (D) a faster CPU

**18.** Swapping moves:
(A) data between registers  (B) files between folders  (C) processes between main memory and the backing store  (D) packets between networks

**19.** Each entry in a segment table contains:
(A) a base and a limit  (B) a frame number only  (C) a page number  (D) an inode

**20.** The relocation (base) register holds the:
(A) largest logical address  (B) page size  (C) process ID  (D) starting physical address of the process

<details><summary><b>Answer key: F</b></summary>

| Q | Ans | Note |
|---|---|---|
| 1 | A | |
| 2 | B | |
| 3 | A | Also called the virtual address |
| 4 | C | Logical memory is divided into pages |
| 5 | A | |
| 6 | B | In the last page |
| 7 | C | Segments are variable-sized (PYQ 2025) |
| 8 | A | Virtual → physical (PYQ 2023) |
| 9 | D | Translation Look-aside Buffer |
| 10 | A | 4 KB = 2¹² |
| 11 | B | 32 − 12 = 20 |
| 12 | A | |
| 13 | C | |
| 14 | D | |
| 15 | A | |
| 16 | B | (PYQ 2023) |
| 17 | A | (PYQ 2025) |
| 18 | C | |
| 19 | A | |
| 20 | D | |
</details>

---

## G. Virtual Memory & Page Replacement

**1.** Virtual memory allows:
(A) a process to run even when it is not completely in memory  (B) a faster CPU  (C) more registers  (D) networking

**2.** Demand paging:
(A) loads all pages at start  (B) loads a page only when it is referenced  (C) never loads pages  (D) loads whole segments

**3.** A page fault occurs when:
(A) the referenced page is not in main memory  (B) the page is already in memory  (C) the CPU has an error  (D) the disk is full

**4.** Thrashing is:
(A) high CPU utilisation  (B) the absence of page faults  (C) so much paging that the CPU spends most of its time swapping pages  (D) deadlock

**5.** Thrashing can be controlled by:
(A) the working-set model / lowering the degree of multiprogramming  (B) adding more processes  (C) a larger time quantum  (D) FCFS scheduling

**6.** Belady's anomaly occurs with:
(A) LRU  (B) Optimal  (C) LFU  (D) FIFO

**7.** Optimal page replacement replaces the page that:
(A) will not be used for the longest time in the future  (B) was used least recently  (C) was loaded first  (D) is used most often

**8.** LRU replaces the page that:
(A) was used most recently  (B) was used least recently  (C) was loaded earliest  (D) is chosen at random

**9.** FIFO replaces the page that:
(A) was used least  (B) will be used last  (C) was loaded earliest  (D) is chosen at random

**10.** Reference string 7, 0, 1, 2, 0, 3, 0, 4 with 3 frames under FIFO. How many page faults?
(A) 6  (B) 7  (C) 8  (D) 5

**11.** The same string with 3 frames under LRU. How many page faults?
(A) 7  (B) 5  (C) 6  (D) 8

**12.** Which algorithm gives the lowest page-fault rate (in theory)?
(A) Optimal  (B) FIFO  (C) LRU  (D) Random

**13.** The dirty (modify) bit shows that a page:
(A) is invalid  (B) is shared  (C) is locked  (D) was modified and must be written to disk before it is replaced

**14.** The valid–invalid bit shows whether a page:
(A) is legal and present in memory  (B) has been modified  (C) is read-only  (D) is shared

**15.** The working set is:
(A) all the pages of a process  (B) the pages referenced in the most recent Δ references  (C) the free frames  (D) the swap space

**16.** Effective memory-access time goes up as the:
(A) page-fault rate rises  (B) TLB hit ratio rises  (C) RAM gets bigger  (D) none of these

**17.** Copy-on-write is used with:
(A) paging out  (B) compaction  (C) fork(), sharing pages until one is written  (D) FCFS scheduling

**18.** The backing store is:
(A) fast secondary storage used as swap space  (B) the cache  (C) a register  (D) ROM

**19.** Pre-paging means:
(A) bringing pages into memory before they are referenced  (B) loading pages only after a fault  (C) never loading pages  (D) loading only on a fault

**20.** An inverted page table has one entry per:
(A) logical page  (B) process  (C) segment  (D) physical frame

<details><summary><b>Answer key: G</b></summary>

| Q | Ans | Note |
|---|---|---|
| 1 | A | |
| 2 | B | A lazy swapper |
| 3 | A | |
| 4 | C | CPU utilisation drops sharply |
| 5 | A | Load control (PYQ 2023/2025) |
| 6 | D | More frames can mean *more* faults |
| 7 | A | Used as a benchmark |
| 8 | B | |
| 9 | C | |
| 10 | B | Faults: 7, 0, 1, 2, (0 hit), 3, 0, 4 → 7 |
| 11 | C | Faults: 7, 0, 1, 2, (0 hit), 3, (0 hit), 4 → 6 |
| 12 | A | |
| 13 | D | |
| 14 | A | |
| 15 | B | |
| 16 | A | |
| 17 | C | |
| 18 | A | |
| 19 | A | |
| 20 | D | |
</details>

---

## H. File Systems

**1.** FAT stands for:
(A) File Access Table  (B) File Allocation Table  (C) Fast Allocation Table  (D) File Address Tree

**2.** NTFS stands for:
(A) New Technology File System  (B) Network Transfer File System  (C) New Table File Structure  (D) Network Technology File Storage

**3.** In UNIX, an inode stores:
(A) the file name  (B) the file contents  (C) the file's metadata and pointers to its data blocks  (D) the directory tree

**4.** In UNIX, the file *name* is stored in:
(A) the directory entry  (B) the inode  (C) the superblock  (D) the boot block

**5.** Contiguous allocation suffers from:
(A) external fragmentation  (B) no random access  (C) pointer overhead in every block  (D) none of these

**6.** The main drawback of linked allocation is:
(A) external fragmentation  (B) no efficient direct (random) access  (C) the need for compaction  (D) none of these

**7.** Indexed allocation uses:
(A) linked pointers  (B) contiguous blocks  (C) only the FAT  (D) an index block holding pointers to all the file's blocks

**8.** FAT is a variation of:
(A) linked allocation  (B) contiguous allocation  (C) indexed allocation  (D) hashed allocation

**9.** Sequential file access works like:
(A) a magnetic tape  (B) random access  (C) hashing  (D) an index

**10.** Basic file operations include:
(A) compile  (B) schedule  (C) create, open, read, write, delete  (D) paging

**11.** In UNIX permissions, "rwx" means:
(A) read, write, execute  (B) read, write, exit  (C) run, write, execute  (D) none of these

**12.** `chmod 755 file` gives the owner which permissions?
(A) rw-  (B) rwx  (C) r-x  (D) r--

**13.** Which directory structure lets files be shared through links?
(A) Single-level  (B) Two-level  (C) Acyclic graph  (D) Linear

**14.** The main problem with a single-level directory is:
(A) naming conflicts, since every file needs a unique name  (B) too much complexity  (C) a slow CPU  (D) none of these

**15.** In data processing, the permanent (perpetual) file of relatively fixed data is the:
(A) temporary file  (B) log file  (C) update file  (D) master file

**16.** Which is a limitation of a traditional file-processing system compared with a DBMS?
(A) Data redundancy and inconsistency  (B) Atomic transactions  (C) Concurrency control  (D) Built-in security

**17.** Which method is used for free-space management?
(A) Page table  (B) Bit vector (bitmap)  (C) TLB  (D) PCB

**18.** A journaling file system:
(A) logs changes before committing them, for crash recovery  (B) keeps no logs  (C) is read-only  (D) works only over a network

**19.** A file with the extension .exe is:
(A) a text file  (B) an image  (C) an executable  (D) an audio file

**20.** The superblock contains:
(A) a user file  (B) user data  (C) a directory  (D) file-system metadata (size, block count, free blocks)

<details><summary><b>Answer key: H</b></summary>

| Q | Ans | Note |
|---|---|---|
| 1 | B | (PYQ 2023, 2024, 2025) |
| 2 | A | (PYQ 2023) |
| 3 | C | (PYQ 2025) |
| 4 | A | |
| 5 | A | |
| 6 | B | |
| 7 | D | |
| 8 | A | The table stores next-block pointers |
| 9 | A | |
| 10 | C | Read, write, modify (PYQ 2023/2025) |
| 11 | A | |
| 12 | B | 7 = rwx, 5 = r-x |
| 13 | C | |
| 14 | A | |
| 15 | D | (PYQ 2025) |
| 16 | A | "Storing space" is not a limitation (PYQ 2025) |
| 17 | B | Also linked list and grouping |
| 18 | A | NTFS, ext4 |
| 19 | C | |
| 20 | D | |
</details>

---

## I. I/O & Disk Management

**1.** SPOOL stands for:
(A) Simultaneous Peripheral Operations On-Line  (B) Simple Peripheral Output On-Line  (C) Serial Process Operation On Line  (D) System Peripheral Operation Overlay

**2.** Spooling is most commonly used for:
(A) the CPU  (B) printers  (C) RAM  (D) cache

**3.** Buffering is used to:
(A) handle the speed mismatch between devices  (B) encrypt data  (C) compile code  (D) route packets

**4.** A buffer cache:
(A) holds the kernel  (B) holds devices  (C) keeps copies of frequently used disk blocks in memory  (D) is a type of file

**5.** DMA lets:
(A) a device transfer data to memory without the CPU handling every byte  (B) only the CPU move data  (C) data bypass memory  (D) none of these

**6.** An interrupt is:
(A) only a program error  (B) a disk  (C) a cache  (D) a signal asking the CPU for attention

**7.** A device driver is:
(A) software that controls a particular hardware device  (B) a hardware part  (C) a compiler  (D) a shell

**8.** Polling means:
(A) using interrupts  (B) the CPU repeatedly checking a device's status  (C) DMA  (D) spooling

**9.** Disk access time equals:
(A) seek time + rotational latency + transfer time  (B) seek time only  (C) transfer time only  (D) latency only

**10.** Seek time is the time taken to:
(A) rotate the disk  (B) transfer data  (C) move the head to the required track  (D) wait in the queue

**11.** Which disk-scheduling algorithm picks the request closest to the current head position?
(A) SSTF  (B) FCFS  (C) SCAN  (D) C-LOOK

**12.** SCAN is also known as the:
(A) circular algorithm  (B) FCFS algorithm  (C) shortest algorithm  (D) elevator algorithm

**13.** In C-SCAN, after reaching one end the head:
(A) jumps back to the start without serving requests on the return trip  (B) serves requests in both directions  (C) moves randomly  (D) none of these

**14.** SSTF disk scheduling can cause:
(A) Belady's anomaly  (B) starvation  (C) thrashing  (D) deadlock

**15.** The head is at cylinder 53. The queue is 98, 183, 37, 122, 14, 124, 65, 67. What is the total head movement under FCFS?
(A) 236  (B) 208  (C) 640  (D) 299

**16.** For the same queue, what is the total head movement under SSTF?
(A) 640  (B) 236  (C) 208  (D) 299

**17.** LOOK differs from SCAN because the head:
(A) goes only as far as the last request in each direction  (B) always goes to the end of the disk  (C) moves randomly  (D) none of these

**18.** RAID stands for:
(A) Random Access Integrated Disk  (B) Rapid Array of Integrated Drives  (C) Redundant Array of Independent Disks  (D) none of these

**19.** RAID 1 is:
(A) striping  (B) parity  (C) none of these  (D) mirroring

**20.** Auxiliary (secondary) storage management deals with:
(A) allocating space on secondary storage devices  (B) CPU registers  (C) IPC  (D) CPU scheduling

<details><summary><b>Answer key: I</b></summary>

| Q | Ans | Note |
|---|---|---|
| 1 | A | |
| 2 | B | Print jobs are queued on disk |
| 3 | A | (PYQ 2019: buffer) |
| 4 | C | (PYQ 2023, 2025) |
| 5 | A | Direct Memory Access |
| 6 | D | |
| 7 | A | |
| 8 | B | Busy-waiting |
| 9 | A | |
| 10 | C | |
| 11 | A | Shortest Seek Time First |
| 12 | D | |
| 13 | A | Gives more uniform waiting time |
| 14 | B | |
| 15 | C | 45 + 85 + 146 + 85 + 108 + 110 + 59 + 2 = 640 |
| 16 | B | 53 → 65 → 67 → 37 → 14 → 98 → 122 → 124 → 183 = 236 |
| 17 | A | |
| 18 | C | |
| 19 | D | RAID 0 = striping, RAID 5 = distributed parity |
| 20 | A | (PYQ 2025) |
</details>

---

## J. Protection, Security & Special-purpose OS

**1.** Protection in an OS means:
(A) controlling which processes/users can access which resources  (B) speeding up the CPU  (C) compiling programs  (D) taking backups

**2.** In an access matrix, the rows are:
(A) objects  (B) domains (users/processes)  (C) access rights  (D) files

**3.** In an access matrix, the columns are:
(A) objects/resources  (B) domains  (C) users  (D) CPUs

**4.** An Access Control List (ACL) is attached to:
(A) each domain  (B) the CPU  (C) each object  (D) memory

**5.** A capability list is attached to:
(A) each domain (row of the matrix)  (B) each object  (C) each file  (D) each disk

**6.** Which of these are authentication methods?
(A) Paging  (B) Swapping  (C) Booting  (D) Passwords, biometrics and OTPs

**7.** The principle of least privilege means:
(A) giving only the minimum rights needed  (B) giving all rights  (C) giving no rights  (D) making everyone an admin

**8.** A Trojan horse is a program that:
(A) spreads by itself (a worm)  (B) looks legitimate but hides malicious code  (C) acts as a firewall  (D) is a security patch

**9.** A trap door (back door) is:
(A) a hidden entry point that bypasses normal security  (B) the normal login screen  (C) a firewall  (D) a log file

**10.** Safeguards in an OS are mechanisms that:
(A) use CPU time efficiently  (B) handle power cuts  (C) protect against unauthorized access and security breaches  (D) speed up I/O

**11.** A multi-user OS:
(A) lets several users use the same system at the same time  (B) supports a single user  (C) runs only one program  (D) is GUI-only

**12.** Which is an example of an embedded OS?
(A) Windows Server  (B) Ubuntu Desktop  (C) macOS  (D) the OS inside a washing machine or car control unit

**13.** Which are mobile operating systems?
(A) Android and iOS  (B) MS-DOS  (C) UNIX V  (D) CP/M

**14.** Which is an example of a network OS?
(A) MS-DOS  (B) Novell NetWare / Windows Server  (C) CP/M  (D) BIOS

**15.** Multimedia systems need hard real-time scheduling:
(A) so that critical tasks are serviced within their timing deadlines  (B) for security  (C) to make files smaller  (D) to reduce cost

**16.** Which disk/CPU scheduling algorithms are used for continuous media?
(A) FCFS  (B) LIFO  (C) EDF and SCAN-EDF  (D) SSTF only

**17.** In a virtual-memory system, load control:
(A) adjusts the degree of multiprogramming to avoid thrashing  (B) adds more processes  (C) forces context switches  (D) none of these

**18.** Which of these is an open-source OS?
(A) Windows  (B) macOS  (C) iOS  (D) Linux

**19.** GUI stands for:
(A) Graphical User Interface  (B) General User Interface  (C) Graphical Unified Input  (D) Guided User Instruction

**20.** Which is a command-line (CLI) operating system?
(A) Windows 11  (B) MS-DOS  (C) Android  (D) iOS

<details><summary><b>Answer key: J</b></summary>

| Q | Ans | Note |
|---|---|---|
| 1 | A | A formal protection model = a mathematical framework (PYQ 2023/2025) |
| 2 | B | |
| 3 | A | |
| 4 | C | Column-wise |
| 5 | A | Row-wise |
| 6 | D | |
| 7 | A | |
| 8 | B | |
| 9 | A | |
| 10 | C | (PYQ 2025) |
| 11 | A | (PYQ 2025) |
| 12 | D | |
| 13 | A | |
| 14 | B | |
| 15 | A | (PYQ 2025) |
| 16 | C | (PYQ 2025) |
| 17 | A | The exam key words it as "CPU time evenly distributed", so check the options (PYQ 2023/2025) |
| 18 | D | |
| 19 | A | |
| 20 | B | |
</details>

---

### Score tracker

| Topic | Attempt 1 | Attempt 2 |
|---|---|---|
| A. OS basics & types | /20 | /20 |
| B. Process & threads | /20 | /20 |
| C. CPU scheduling | /20 | /20 |
| D. Synchronization | /20 | /20 |
| E. Deadlocks | /20 | /20 |
| F. Memory management | /20 | /20 |
| G. Virtual memory | /20 | /20 |
| H. File systems | /20 | /20 |
| I. I/O & disk | /20 | /20 |
| J. Protection & special OS | /20 | /20 |
| **Total** | **/200** | **/200** |
