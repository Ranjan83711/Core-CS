# Bihar STET Paper 2 (Computer Science): Digital Logic & Computer Organization PYQ Bank

**Papers covered:** the same 8 papers as the earlier chapters.

| Year | Paper | Questions found |
|---|---|---|
| 2019 | Second sitting | 20 (computer fundamentals and Boolean basics) |
| 2020 | Re-exam | 19 (computer fundamentals and hardware) |
| 2023 | 12 Sep, Shift 1 | 13 |
| 2024 | 11 Jun (memory-based) | 5 |
| 2025 | 3 Nov Shift 1 | 10 |
| 2025 | 3 Nov Shift 2 | 8 |
| 2025 | 4 Nov Shift 2 | 10 |
| 2025 | 7 Nov Shift 1 | 6 |
| **Total** | | **≈91** |

> **This is the largest pool across all years.** The style changed over time:
> - **2019–2020** asked basic *computer fundamentals*: generations, inventors, memory types and full forms.
> - **2023–2025** ask *digital logic and microprocessor/COA* theory: K-maps, adders, codes, complements, addressing modes, PLA/FPGA and Harvard architecture.
>
> Expect **6–10 questions per shift**.

> ⚠️ **Important: the K-map / Boolean simplification questions in 2023 and 2025 have broken options.** The same question bank is reused, and most of the "simplified expression" options are **mathematically wrong**. The 2023 official key still marked one of them. This file gives:
> 1. the **correct** simplification, so you understand the method, and
> 2. the **option the official key chose**, so you can recognise it if the same question repeats.

**Notes on answers**
- The questions are paraphrased.
- The 2023 answers come from the official key.
- The 2025 answers were worked out from the options.
- The 2019 and 2020 answers are standard textbook answers, because the candidates' pen marks were often wrong.

---

## 1. Topic frequency

| Rank | Topic | Times asked | Years |
|---|---|---|---|
| 1 | **Computer fundamentals** (generations, inventors, UNIVAC/ENIAC, characteristics, input/output devices, SMPS, motherboard, floppy) | 25 | 2019, 2020 |
| 2 | **Boolean algebra & K-maps** (SOP/POS simplification ×8, De Morgan, K-map groups, don't cares, A·A, + = OR) | 16 | 2019, 2023, 2024, 2025 ×4 |
| 3 | **Number systems, codes & complements** (hex→binary, 1's/2's complement, Excess-3, Gray↔binary, EBCDIC, byte, borrow) | 12 | 2019, 2023, 2024, 2025 ×3 |
| 4 | **Microprocessor/CPU organisation** (ALU, accumulator ×2, data bus, addressing mode, 8086, CPU = CU + ALU, address bus) | 10 | 2020, 2023, 2025 ×4 |
| 5 | **Memory & storage** (ROM vs RAM ×2, CD-ROM, magnetic disk, HDD vs SSD, buffer, memory holds data/instructions) | 9 | 2019, 2020, 2023, 2025 |
| 6 | **Combinational circuits & PLDs** (full adder, carry look-ahead ×2, PLA ×2, FPGA, priority encoder) | 7 | 2023, 2025 ×3 |
| 7 | **Microcontrollers** (automotive ×2, home automation, memory-mapped I/O, Harvard architecture) | 5 | 2023, 2025 ×2 |
| 8 | **Logic families** (TTL voltage, CMOS) | 2 | 2023, 2025 |

---

## 2. Questions by topic (with answers)

### A. Boolean algebra & K-map
| # | Asked (paraphrased) | Correct answer | Official key / note | Year |
|---|---|---|---|---|
| 1 | F(A,B,C,D) = Σ(0,1,2,4,5,6,8,9,10,12,13,14), simplified | **C′ + D′** (only 3, 7, 11 and 15 are missing, i.e. the CD = 11 cells) | The 2023 key picked "A′B′C′D′ + A′B′C′D + A′BC′D + AB′C′D + ABCD" (wrong, but marked) | 2023, 2025 (7 Nov) |
| 2 | F(A,B,C) = Σ(0,1,2,3,5), SOP | **A′ + B′C** | The 2023 key picked "A′B′ + AB′ + AB + AC" | 2023, 2025 (7 Nov) |
| 3 | F(A,B,C) = Σ(0,1,3,5), simplified SOP | **A′B′ + A′C + B′C** | None of the options is correct | 2025 (3 Nov S2) |
| 4 | F(A,B,C) = Σ(1,2,4,6), POS | Π(0,3,5,7). Simplified SOP: **A′B′C + BC′ + AC′** | None of the options is correct | 2025 (3 Nov S1) |
| 5 | F(A,B,C) = Σ(0,2,4,5,7), simplified POS | **(A + C′)(A′ + B′ + C)** (zeros at 1, 3, 6) | None of the options is correct | 2025 (4 Nov) |
| 6 | F(A,B,C,D) = Σ(0,1,2,3,8,9,10,11), simplified | **B′** | None of the options is correct | 2025 (4 Nov) |
| 7 | F = Σ(0,1,2,4,5,6,10,12,13), K-map | (memory-based, no options) | — | 2024 |
| 8 | A = 101010, B = 111111: (A AND B) OR (A XOR B) | **111111** | Option A | 2025 (3 Nov S1) |
| 9 | A = 110001, B = 001100: (A·B) + (A′·B′) (= XNOR) | **000010** | None of the memory-based options matched | 2024 |
| 10 | De Morgan's theorems help simplify expressions with many | **Variables** (complemented groups) | Likely key A | 2025 (3 Nov S2) |
| 11 | K-map term for a set of adjacent cells that can be combined | **Group** (pair = 2, quad = 4, octet = 8) | Option D | 2025 (3 Nov S2) |
| 12 | Grouping cells that look non-adjacent but share a variable | Wrap-around grouping. The options (pair, quad, octet, group) are unclear; "octet" is the most likely key. | Unclear | 2025 (4 Nov) |
| 13 | Purpose of don't-care conditions | **They mark input combinations whose output is undefined (can be 0 or 1)** | Option B | 2025 (4 Nov) |
| 14 | A·A = | **A** | | 2019 |
| 15 | The "+" sign in Boolean algebra means | **OR** | | 2019 |
| 16 | Boolean AND operator symbol (+, −, /, *) | **· (shown as *)** | | 2019 |

### B. Number systems, codes & arithmetic
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Hex F4 in binary | **1111 0100** | 2025 (7 Nov) |
| 2 | Range of n-bit 1's complement | **−(2ⁿ⁻¹ − 1) to +(2ⁿ⁻¹ − 1)**. The options only gave the 2's-complement range −2ⁿ⁻¹ to 2ⁿ⁻¹ − 1; pick that if forced. | 2025 (3 Nov S1) |
| 3 | 2's-complement addition with a carry out of the MSB | Textbook: **ignore the carry**. The 2023 key said "add the carry to the LSB" (that's the 1's-complement rule). Read the options carefully. | 2023, 2024, 2025 (7 Nov) |
| 4 | Excess-3 is self-complementing because | **Inverting the bits gives the 9's complement** | 2025 (3 Nov S1) |
| 5 | Gray code → binary uses | **XOR** | 2023, 2025 (3 Nov S2) |
| 6 | Binary subtraction: borrowing from a digit that is 1 | **That digit becomes 0** | 2025 (7 Nov) |
| 7 | Binary multiplication: first step after aligning | **Multiply the LSB of the multiplier** (2023 key) | 2023 |
| 8 | Hamming code: parity-bit distance vs capability | 2023 key: "closer parity bits → lower correction capability" | 2023 |
| 9 | EBCDIC stands for | **Extended Binary Coded Decimal Interchange Code** | 2019 |
| 10 | EBCDIC is used by | **Mainframe computers** | 2019 |
| 11 | 1 byte = | **8 bits** | 2019 |
| 12 | Binary → Gray conversion | MSB stays the same, then XOR adjacent bits | 2024 |

### C. CPU / microprocessor organisation
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Where the ALU is located | **CPU** | 2025 (3 Nov S1) |
| 2 | Register that holds data during arithmetic/logic operations | **Accumulator** | 2023, 2025 (4 Nov) |
| 3 | Data-bus width is measured in | **Bits** | 2023, 2025 (3 Nov S1) |
| 4 | Operand given inside the instruction itself | **Immediate addressing** | 2025 (3 Nov S1) |
| 5 | Year of the Intel 8086 | **1978**. Not among the options (1971/1981/1986/1991); 1971 was the 4004. | 2025 (3 Nov S2) |
| 6 | The ALU acts on commands from the | **Control unit** | 2019 |
| 7 | A CPU contains | **Control unit + ALU** | 2020 |
| 8 | Physical connection between the microprocessor, memory and other parts | **Bus** (address bus in the key) | 2020 |
| 9 | Brain of the computer | **CPU** | 2019 |
| 10 | Memory holds data and instructions temporarily | **Memory** | 2023 |

### D. Combinational circuits & programmable logic
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Inputs to a full adder | **3** (A, B, Cin) | 2025 (3 Nov S2) |
| 2 | Adder that removes ripple-carry delay | **Carry look-ahead adder** | 2025 (3 Nov S2) |
| 3 | Advantage of carry look-ahead | **Faster (less propagation delay)** | 2025 (4 Nov) |
| 4 | Gates used in a PLA | **AND gates and OR gates** | 2023, 2025 (4 Nov) |
| 5 | Technology with the highest customisation | **FPGA** | 2025 (3 Nov S2) |
| 6 | A priority encoder | **Assigns priority to input lines (outputs the code of the highest-priority active input)** | 2025 (7 Nov) |

### E. Logic families
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Logic family using depletion and enhancement MOSFETs | **CMOS** (2023 key; strictly, NMOS uses depletion loads) | 2023 |
| 2 | Operating voltage of TTL | Standard TTL = **5 V**. The official 2025 key marked "**5.0 V to 12 V**". | 2025 (3 Nov S1) |

### F. Microcontrollers
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Microcontroller use in cars | **Engine control** | 2023, 2025 (3 Nov S1) |
| 2 | Microcontroller use in home automation | **Temperature and lighting control** | 2025 (4 Nov) |
| 3 | Memory-mapped I/O | **I/O devices share the memory address space** (options: "lets external devices access the microcontroller's memory") | 2025 (3 Nov S1) |
| 4 | Harvard architecture | **Separate memory for instructions and data** | 2025 (4 Nov) |

### G. Memory & storage
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | ROM vs RAM | **ROM is permanent/non-volatile; RAM is volatile read-write** | 2023 |
| 2 | The two kinds of main memory | **RAM and ROM** | 2019 |
| 3 | CD-ROM is a | **Optical memory**. Options were semiconductor/register/magnetic/none, so the answer is **None of these**. | 2019 |
| 4 | Magnetic-disk capacity depends on | **All of these** (tracks per inch, bits per inch, …) | 2019 |
| 5 | Area that buffers speed differences | **Buffer** | 2019 |
| 6 | HDD vs SSD | **All of the above** (spinning platters vs flash, SSD faster, SSD more durable) | 2025 (4 Nov) |
| 7 | Magnetic disks are the most popular medium for | **Direct access** | 2020 |
| 8 | Capacity of a high-density double-sided floppy | **1.44 MB** | 2020 |
| 9 | Storage device holding the most data (floppy, HDD, CD, MO disk) | **Hard disk** | 2020 |

### H. Computer fundamentals (2019–2020 style)
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | UNIVAC | **Universal Automatic Computer** | 2019 |
| 2 | Basic operations of a computer | **All of these** (arithmetic, logical, storage) | 2019 |
| 3 | Inventor of the Difference Engine / father of the computer | **Charles Babbage** | 2019 |
| 4 | Generation that used microprocessors | **Fourth** | 2019 |
| 5 | ICs belong to which generation? | **Third** (SSI and MSI) | 2019 |
| 6 | Main component of 1st-generation computers | **Vacuum tubes** | 2019, 2020 |
| 7 | Computer free from tiredness and boredom | **Diligence** | 2019 |
| 8 | Hybrid computer | **Combines digital and analog** | 2019 |
| 9 | CAD printing and drawing uses | **Digital plotter** | 2020 |
| 10 | Not an input device (OCR, scanner, voice, COM) | **COM (Computer Output to Microfilm)** | 2020 |
| 11 | Accuracy of floating point in two 16-bit words | **≈ 6 digits** | 2020 |
| 12 | Board holding the CPU, memory and slots | **Motherboard** | 2020 |
| 13 | A VDU is | **An output device** | 2020 |
| 14 | A modern computer is meant for | **Input, storage, processing and output of data** | 2020 |
| 15 | Vacuum tube invented in | **1906** (triode, Lee de Forest) | 2020 |
| 16 | A dumb terminal has | **A keyboard and a screen** (no processing of its own) | 2020 |
| 17 | 1 millisecond = | **1/1000 of a second** | 2020 |
| 18 | Computers are reliable but not | **Infallible** | 2020 |
| 19 | Special-purpose computer | **ABC (Atanasoff–Berry Computer)** | 2020 |
| 20 | SMPS | **Switched Mode Power Supply** | 2020 |
| 21 | Considered the first electronic computer until the 1973 patent ruling | **ENIAC** | 2020 |

---

## 3. Must-revise checklist

1. **Number systems:** conversions between binary, octal, decimal and hex (including fractions); bits/bytes/KB = 1024.
2. **Complements:**
   - 1's (invert) and 2's (invert + 1).
   - Ranges: 2's = −2ⁿ⁻¹…2ⁿ⁻¹−1; 1's and sign-magnitude = ±(2ⁿ⁻¹−1).
   - End-around carry (1's) vs discarded carry (2's), and overflow detection.
3. **Codes:** BCD (8421), Excess-3 (self-complementing), Gray (one-bit change; binary↔Gray by XOR), ASCII (7-bit, A = 65, a = 97), EBCDIC (8-bit, mainframes), parity, Hamming (7,4).
4. **Boolean algebra:** identities, absorption, De Morgan, duality, universal gates (NAND/NOR, and gate counts), XOR/XNOR.
5. **K-maps:** Gray-code ordering, pair/quad/octet (remove 1/2/3 variables), wrap-around, don't cares, minterms/maxterms, SOP ↔ POS, Quine–McCluskey.
6. **Combinational:** half and full adder/subtractor, ripple-carry vs carry look-ahead, MUX (2ⁿ:1 → n select lines), DEMUX, decoder, encoder, priority encoder, comparator, ROM/PROM/PAL/PLA/FPGA.
7. **Sequential:** latch vs flip-flop, SR (invalid S=R=1), JK (toggle, race-around → master–slave), D, T, registers (SISO/SIPO/PISO/PIPO), counters (async/sync, mod-N, ring n states, Johnson 2n states).
8. **CPU:** ALU, CU, registers (PC, IR, MAR, MDR, accumulator, flags), buses (address = unidirectional, data = bidirectional; 2ⁿ locations), instruction cycle, addressing modes (immediate, direct, indirect, register, indexed, relative), Von Neumann vs Harvard, RISC vs CISC, Flynn (SISD/SIMD/MISD/MIMD).
9. **Memory:** hierarchy, SRAM vs DRAM, ROM/PROM/EPROM (UV)/EEPROM, cache (locality, hit ratio), virtual memory, HDD vs SSD, optical media, DMA, interrupts, memory-mapped vs isolated I/O.
10. **Fundamentals:** generations (vacuum tube → transistor → IC → VLSI microprocessor → AI), Babbage, ENIAC/UNIVAC/ABC, 4004 (1971) / 8085 (8-bit) / 8086 (16-bit, 1978), logic families (TTL 5 V, CMOS low power, ECL fastest).

Practice set: `06b_Digital_Logic_COA_Practice_MCQs.md`
