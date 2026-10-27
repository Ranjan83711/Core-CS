# Bihar STET Paper 2 (Computer Science): Operating System PYQ Bank

**Papers covered:** the same 8 papers as the Computer Networks bank, listed below.

| Year | Paper | OS questions found |
|---|---|---|
| 2019 | Second sitting (Sets A/H) | 2 |
| 2020 | Re-exam (Set B) | 1 |
| 2023 | 12 Sep, Shift 1 | 9 |
| 2024 | 11 Jun (memory-based list) | 1 |
| 2025 | 3 Nov Shift 1 | 7 |
| 2025 | 3 Nov Shift 2 | 7 |
| 2025 | 4 Nov Shift 2 | 9 |
| 2025 | 7 Nov Shift 1 | 5 |
| **Total** | | **≈41** |

> **Pattern:** 2019 and 2020 asked almost nothing on OS. Since 2023, every shift has had **5–9 OS questions**, so plan for about 7 marks.
> The questions are **conceptual, one-line definitions** (what X is used for). There were **no numericals** (scheduling Gantt charts, page faults) in these papers. Practise a few anyway in case the style changes.

**Notes on answers**
- The questions are paraphrased.
- The 2023 answers come from the official key.
- For the 2025 papers, only the options were readable, not the answer marks. Those answers were worked out from the options and are the standard textbook ones.

---

## 1. Topic frequency

| Rank | Topic | Times asked | Years |
|---|---|---|---|
| 1 | **File systems** (FAT, NTFS, inode, file operations, master file, file server, file system vs DBMS) | 10 | 2023, 2024, 2025 ×4 |
| 2 | **Process synchronization** (monitors, semaphore/critical section, dining philosophers, producer–consumer, goal of synchronization) | 6 | 2025 ×3 |
| 3 | **Memory management** (paging, page table, segmentation, overlays, fixed partitions → fragmentation, memory map) | 7 | 2023, 2025 ×3 |
| 4 | **I/O & storage management** (I/O subsystem, buffer cache, buffer, auxiliary storage) | 6 | 2019, 2023, 2025 ×3 |
| 5 | **OS basics, types & protection** (kernel/supervisor mode, multi-user, DOS, Android, safeguards, formal protection model) | 6 | 2019, 2020, 2023, 2025 ×2 |
| 6 | **Process management** (context switching, IPC) | 2 | 2025 ×2 |
| 7 | **Scheduling, real-time & multimedia OS** (hard real-time scheduling, EDF/SCAN-EDF, load control) | 4 | 2023, 2025 ×3 |
| — | **Deadlock, virtual memory/page replacement, disk scheduling** | 0 so far | Standard syllabus. Likely to appear, so they're covered in the practice set. |

---

## 2. Questions by topic (with answers)

### A. File systems
| # | Asked (paraphrased) | Answer | Year |
|---|---|---|---|
| 1 | Full form of FAT | **File Allocation Table** | 2023, 2024, 2025 (3 Nov S1) |
| 2 | Full form of NTFS | New Technology File System | 2023 |
| 3 | What an inode stores (Unix) | **The file's attributes/metadata** (not its name or contents) | 2025 (3 Nov S1) |
| 4 | File-manipulation operations in an OS include | **Reading, writing and modifying file content** | 2023, 2025 (3 Nov S1) |
| 5 | Which is **not** a limitation of a file system (redundancy, inconsistency, data dependence, storing space)? | **Storing space** | 2025 (3 Nov S1) |
| 6 | A file is a collection of related… | **Records** | 2024, 2025 (3 Nov S2) |
| 7 | The perpetual (permanent) file in an information system | **Master file** | 2025 (7 Nov) |
| 8 | Resource **not** necessarily needed on a file server | **Monitor** | 2025 (4 Nov) |
| 9 | Data structure showing allocation status of main memory | **Memory map** | 2025 (3 Nov S1) |

### B. Process synchronization
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Who introduced monitors? (options: Dijkstra, Turing, Berners-Lee, Torvalds) | **Dijkstra** is the best option offered. In textbooks, monitors are credited to **Hoare & Brinch Hansen**, and Dijkstra gave semaphores. | 2025 (3 Nov S2) |
| 2 | Monitors are used to achieve | **Mutual exclusion and synchronization** | 2025 (4 Nov) |
| 3 | Dining philosophers is a synchronization problem about | **Mutual exclusion** (deadlock and starvation when sharing resources) | 2025 (3 Nov S2) |
| 4 | Producer–consumer problem involves | **Two processes exchanging data through a shared buffer** | 2025 (7 Nov) |
| 5 | Acquiring a semaphore and entering the critical section with mutual exclusion is called | **Critical-section synchronization** | 2025 (7 Nov) |
| 6 | Goal of synchronization in parallel programming | Coordinate access to shared data so that results are correct (avoid races/deadlock) | 2025 (4 Nov) |

### C. Memory management
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Purpose of a page table | **Translate virtual (logical) addresses to physical addresses** | 2023 |
| 2 | Technique using fixed-size blocks; a process can go into any free block | **Paging** | 2025 (3 Nov S2) |
| 3 | In segmentation, each segment is | **A variable-sized block** (logical unit) | 2025 (4 Nov) |
| 4 | Main advantage of overlays | **Large programs can run in limited memory** | 2025 (3 Nov S2) |
| 5 | Fixed-partition multiprogramming: process bigger than the partition → | **Fragmentation** (official key) | 2023 |
| 6 | Allocation status of main memory is shown by | **Memory map** | 2025 (3 Nov S1) |
| 7 | Load control's goal (official key) | "Ensure CPU time is evenly distributed among processes." In textbooks, load control limits the degree of multiprogramming to prevent **thrashing**. Pick the key's option if the question repeats. | 2023, 2025 (7 Nov) |

### D. I/O & storage management
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | The I/O subsystem is responsible for | **Managing I/O between processes and I/O devices** | 2023, 2025 (7 Nov) |
| 2 | A buffer cache is used to | **Keep copies of frequently used disk data/files in memory** | 2023, 2025 (4 Nov) |
| 3 | Storage area that compensates for speed differences between devices | **Buffer** | 2019 |
| 4 | Auxiliary storage management involves | **Allocating space on secondary storage devices** | 2025 (3 Nov S2) |

### E. OS basics, types & protection
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | The kernel's privileged mode is also called | **Supervisor mode** (kernel mode) | 2025 (3 Nov S1) |
| 2 | "Multi-user" OS means | **Several users can work on the same machine** | 2025 (4 Nov) |
| 3 | DOS stands for | Disk Operating System | 2019 |
| 4 | Android is a/an | **Operating system** | 2020 |
| 5 | Safeguards in an OS protect against | **Unauthorized access and security breaches** | 2025 (4 Nov) |
| 6 | A formal model of protection provides | **A mathematical framework for analysing resource allocation/access** | 2023, 2025 (4 Nov) |

### F. Process management
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Context switching means | **Switching the CPU between processes to allow multitasking** | 2025 (3 Nov S1) |
| 2 | IPC is used for | **Letting processes exchange information and synchronize** | 2025 (3 Nov S2) |

### G. Scheduling / real-time / multimedia OS
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Why multimedia needs hard real-time scheduling | **So critical tasks are serviced within their deadlines** | 2025 (4 Nov) |
| 2 | Algorithms for the deadlines and rate needs of continuous media | **Both EDF and SCAN-EDF** | 2025 (3 Nov S2) |
| 3 | Load control (see C-7) | | 2023, 2025 |

---

## 3. Must-revise checklist

1. **OS basics:** kernel vs shell, user vs kernel (supervisor) mode, system calls, booting/bootstrap loader, types (batch, multiprogramming, time-sharing, multiprocessing, distributed, real-time hard/soft, embedded, mobile, network OS).
2. **Process:** PCB, 5 states and transitions, context switch, schedulers (long/short/medium-term), dispatcher, threads vs processes, fork/exec, zombie/orphan, IPC (shared memory, message passing, pipes).
3. **Scheduling:** FCFS (convoy effect), SJF/SRTF (optimal average wait), Priority (starvation → aging), Round Robin (time quantum), multilevel (feedback) queues, EDF/Rate-Monotonic. Formulas: TAT = CT − AT, WT = TAT − BT.
4. **Synchronization:** critical section (mutual exclusion, progress, bounded waiting), race condition, semaphores (Dijkstra, P/V, binary/counting), mutex, monitors (Hoare/Brinch Hansen), Peterson's solution, Test-and-Set, classic problems (producer–consumer/bounded buffer, readers–writers, dining philosophers, sleeping barber).
5. **Deadlock:** 4 Coffman conditions, resource-allocation graph, prevention/avoidance (Banker's algorithm, safe state)/detection/recovery, minimum resources n(k−1)+1.
6. **Memory:** logical vs physical address, MMU, contiguous allocation (first/best/worst fit), internal vs external fragmentation, compaction, paging (page/frame, page table, TLB), segmentation (base/limit), overlays, swapping.
7. **Virtual memory:** demand paging, page fault, thrashing (working set), page replacement (FIFO + Belady's anomaly, Optimal, LRU), dirty bit.
8. **File system:** FAT, NTFS, inode, directory structures, allocation (contiguous/linked/indexed), free-space bitmap, permissions (rwx, chmod).
9. **I/O & disk:** spooling, buffering, buffer cache, DMA, interrupts vs polling, disk scheduling (FCFS, SSTF, SCAN/elevator, C-SCAN, LOOK), RAID.
10. **Protection:** access matrix, ACL vs capability list, least privilege, safeguards.

Practice set: `02b_Operating_System_Practice_MCQs.md`
