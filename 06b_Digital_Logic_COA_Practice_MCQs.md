# Digital Logic & Computer Organization: Practice MCQs (200 questions)

**Bihar STET Paper 2 (Computer Science)**

There are 10 topics with 20 questions each. The answer is shown right under each question, so you can revise in one read. Target: 17/20 or better.

Do conversions and K-maps **on paper**. Every K-map answer here has been checked minterm by minterm.

---

## A. Number Systems

**1.** (1011)₂ = ?
(A) 9  (B) 10  (C) 11  (D) 13

✅ **Ans: (C) 11** — 8 + 2 + 1

**2.** (25)₁₀ = ? in binary
(A) 11001  (B) 10101  (C) 11010  (D) 10011

✅ **Ans: (A) 11001** — 16 + 8 + 1

**3.** (F4)₁₆ = ? in binary
(A) 11111001  (B) 11110100  (C) 11111100  (D) 11111010

✅ **Ans: (B) 11110100** — F = 1111, 4 = 0100 (PYQ 2025)

**4.** (157)₈ = ? in decimal
(A) 157  (B) 103  (C) 117  (D) 111

✅ **Ans: (D) 111** — 64 + 40 + 7

**5.** (2A)₁₆ = ? in decimal
(A) 32  (B) 42  (C) 26  (D) 52

✅ **Ans: (B) 42** — 2×16 + 10

**6.** (11011)₂ = ? in octal
(A) 33  (B) 27  (C) 36  (D) 63

✅ **Ans: (A) 33** — 011 011

**7.** (10111110)₂ = ? in hex
(A) EB  (B) B6  (C) BE  (D) 9E

✅ **Ans: (C) BE** — 1011 = B, 1110 = E

**8.** What is the base of the hexadecimal system?
(A) 8  (B) 10  (C) 16  (D) 2

✅ **Ans: (C) 16**

**9.** What is the largest digit in the octal system?
(A) 7  (B) 8  (C) 9  (D) F

✅ **Ans: (A) 7**

**10.** (0.5)₁₀ = ? in binary
(A) 0.01  (B) 0.1  (C) 0.11  (D) 1.1

✅ **Ans: (B) 0.1**

**11.** (0.101)₂ = ? in decimal
(A) 0.5  (B) 0.625  (C) 0.75  (D) 0.125

✅ **Ans: (B) 0.625** — 0.5 + 0.125

**12.** What is the minimum number of bits needed to represent decimal 100?
(A) 6  (B) 8  (C) 10  (D) 7

✅ **Ans: (D) 7** — 2⁷ = 128 > 100

**13.** One nibble equals:
(A) 4 bits  (B) 8 bits  (C) 2 bits  (D) 16 bits

✅ **Ans: (A) 4 bits**

**14.** 1 KB equals:
(A) 1000 bytes  (B) 1024 bytes  (C) 512 bytes  (D) 2048 bytes

✅ **Ans: (B) 1024 bytes**

**15.** (77)₈ = ? in hex
(A) 3F  (B) 77  (C) 4D  (D) 3E

✅ **Ans: (A) 3F** — 63 decimal

**16.** (FF)₁₆ = ? in decimal
(A) 256  (B) 15  (C) 255  (D) 1515

✅ **Ans: (C) 255**

**17.** How many hex digits does a 16-bit number need?
(A) 2  (B) 4  (C) 8  (D) 16

✅ **Ans: (B) 4** — 4 bits per hex digit

**18.** (1000)₂ + (0111)₂ = ?
(A) 1111  (B) 1110  (C) 10000  (D) 0111

✅ **Ans: (A) 1111** — 8 + 7 = 15

**19.** What is the radix of the binary system?
(A) 2  (B) 8  (C) 10  (D) 16

✅ **Ans: (A) 2**

**20.** 1 MB equals:
(A) 2¹⁰ bytes  (B) 2³⁰ bytes  (C) 10³ bytes  (D) 2²⁰ bytes

✅ **Ans: (D) 2²⁰ bytes**

---

## B. Binary Arithmetic & Complements

**1.** What is the 1's complement of 1010?
(A) 0101  (B) 0110  (C) 1011  (D) 1010

✅ **Ans: (A) 0101** — Invert every bit

**2.** What is the 2's complement of 1010?
(A) 0101  (B) 0110  (C) 1011  (D) 1001

✅ **Ans: (B) 0110** — 0101 + 1

**3.** What is the 2's complement of 00101100?
(A) 11010011  (B) 00101101  (C) 11010100  (D) 11010101

✅ **Ans: (C) 11010100** — Invert to 11010011, then add 1

**4.** What range can an n-bit 2's-complement number represent?
(A) −2ⁿ⁻¹ to 2ⁿ⁻¹ − 1  (B) 0 to 2ⁿ − 1  (C) −2ⁿ⁻¹ to 2ⁿ⁻¹  (D) −2ⁿ to 2ⁿ − 1

✅ **Ans: (A) −2ⁿ⁻¹ to 2ⁿ⁻¹ − 1**

**5.** What range can an n-bit 1's-complement number represent?
(A) −2ⁿ⁻¹ to 2ⁿ⁻¹ − 1  (B) 0 to 2ⁿ − 1  (C) −2ⁿ⁻¹ to 2ⁿ⁻¹  (D) −(2ⁿ⁻¹ − 1) to +(2ⁿ⁻¹ − 1)

✅ **Ans: (D) −(2ⁿ⁻¹ − 1) to +(2ⁿ⁻¹ − 1)** — (PYQ 2025: correct range)

**6.** What is the range of an 8-bit 2's-complement number?
(A) −128 to 127  (B) −127 to 127  (C) 0 to 255  (D) −255 to 255

✅ **Ans: (A) −128 to 127**

**7.** How many representations of zero does 1's complement have?
(A) one  (B) two (+0 and −0)  (C) none  (D) three

✅ **Ans: (B) two (+0 and −0)**

**8.** In 2's-complement addition, the carry out of the MSB is:
(A) added to the LSB  (B) added to the sign bit  (C) discarded  (D) subtracted from the MSB

✅ **Ans: (C) discarded** — Textbook rule. The 2023 key said "add to the LSB", which is the 1's-complement rule.

**9.** In 1's-complement addition, the end-around carry is:
(A) added to the LSB  (B) discarded  (C) added to the MSB  (D) ignored only when negative

✅ **Ans: (A) added to the LSB**

**10.** 1011 + 0110 = ?
(A) 10001  (B) 1101  (C) 10011  (D) 1111

✅ **Ans: (A) 10001** — 11 + 6 = 17

**11.** 1101 − 0110 = ?
(A) 0110  (B) 0111  (C) 1001  (D) 0101

✅ **Ans: (B) 0111** — 13 − 6 = 7

**12.** 101 × 11 = ?
(A) 1011  (B) 1110  (C) 1101  (D) 1111

✅ **Ans: (D) 1111** — 5 × 3 = 15

**13.** In 2's-complement addition, overflow happens when:
(A) the carry into the MSB differs from the carry out of the MSB  (B) there is any carry out  (C) the result is zero  (D) both numbers are negative

✅ **Ans: (A) the carry into the MSB differs from the carry out of the MSB**

**14.** Adding two positive numbers and getting a negative result means:
(A) underflow  (B) overflow  (C) a normal carry  (D) none of these

✅ **Ans: (B) overflow**

**15.** What is −5 in 8-bit 2's complement?
(A) 10000101  (B) 11111010  (C) 11111011  (D) 00000101

✅ **Ans: (C) 11111011** — 00000101 → invert to 11111010 → +1

**16.** What is −5 in 8-bit sign-magnitude?
(A) 10000101  (B) 11111011  (C) 11111010  (D) 01111011

✅ **Ans: (A) 10000101**

**17.** What is the 9's complement of 7?
(A) 2  (B) 3  (C) 7  (D) 9

✅ **Ans: (A) 2** — 9 − 7

**18.** What is the 10's complement of 345?
(A) 654  (B) 655  (C) 645  (D) 555

✅ **Ans: (B) 655** — 999 − 345 + 1

**19.** In binary subtraction, when you borrow from a digit that is 1, that digit:
(A) stays the same  (B) increases by 1  (C) stays 1  (D) becomes 0

✅ **Ans: (D) becomes 0** — (PYQ 2025)

**20.** How many bits does IEEE-754 single precision use?
(A) 32  (B) 64  (C) 16  (D) 128

✅ **Ans: (A) 32** — 1 sign + 8 exponent + 23 mantissa bits

---

## C. Codes

**1.** What is the BCD code for 59?
(A) 0101 1001  (B) 0011 1011  (C) 0101 1010  (D) 1001 0101

✅ **Ans: (A) 0101 1001** — 5 → 0101, 9 → 1001

**2.** BCD is a weighted code with weights:
(A) 2421  (B) 8421  (C) Excess-3  (D) Gray

✅ **Ans: (B) 8421**

**3.** Which of these is an invalid BCD code?
(A) 1001  (B) 0111  (C) 1010  (D) 0000

✅ **Ans: (C) 1010** — BCD only uses 0000–1001

**4.** What is the Excess-3 code for decimal 4?
(A) 0100  (B) 0111  (C) 1000  (D) 0011

✅ **Ans: (B) 0111** — 4 + 3 = 7

**5.** Excess-3 is self-complementing because:
(A) inverting the bits of a code gives the code for its 9's complement  (B) it converts directly to ASCII  (C) it is used in finance  (D) it is a Gray code

✅ **Ans: (A) inverting the bits of a code gives the code for its 9's complement** — (PYQ 2025)

**6.** In Gray code, consecutive numbers differ in:
(A) exactly one bit  (B) two bits  (C) all bits  (D) no bits

✅ **Ans: (A) exactly one bit**

**7.** Binary 1011 in Gray code is:
(A) 1101  (B) 1011  (C) 0111  (D) 1110

✅ **Ans: (D) 1110** — 1, 1⊕0 = 1, 0⊕1 = 1, 1⊕1 = 0

**8.** Gray code 1101 in binary is:
(A) 1001  (B) 1011  (C) 1101  (D) 1110

✅ **Ans: (A) 1001** — 1, 1⊕1 = 0, 0⊕0 = 0, 0⊕1 = 1

**9.** Which operation converts Gray code to binary?
(A) Subtraction  (B) Addition  (C) XOR  (D) Division

✅ **Ans: (C) XOR** — (PYQ 2023, 2025)

**10.** Standard ASCII is a code of how many bits?
(A) 7  (B) 8  (C) 16  (D) 4

✅ **Ans: (A) 7**

**11.** EBCDIC stands for:
(A) Extended Bit Code Decimal Interchange Code  (B) Extended Binary Coded Decimal Interchange Code  (C) Extended Binary Case Decimal Interchange Code  (D) Extended Bit Case Decimal Interchange Code

✅ **Ans: (B) Extended Binary Coded Decimal Interchange Code** — (PYQ 2019)

**12.** EBCDIC was used mainly in:
(A) microcomputers  (B) minicomputers  (C) mainframe computers  (D) supercomputers

✅ **Ans: (C) mainframe computers** — (PYQ 2019)

**13.** Unicode can represent:
(A) the characters of nearly all world languages  (B) only English  (C) only digits  (D) only 128 characters

✅ **Ans: (A) the characters of nearly all world languages**

**14.** What is the ASCII value of 'A'?
(A) 65  (B) 97  (C) 48  (D) 66

✅ **Ans: (A) 65**

**15.** What is the ASCII value of 'a'?
(A) 65  (B) 48  (C) 98  (D) 97

✅ **Ans: (D) 97**

**16.** With even parity, what is the parity bit for 1101001?
(A) 0  (B) 1  (C) 2  (D) none

✅ **Ans: (A) 0** — It already has four 1s

**17.** Which of these is a weighted code?
(A) 8421 BCD  (B) Excess-3  (C) Gray  (D) ASCII

✅ **Ans: (A) 8421 BCD**

**18.** Which two are unweighted codes?
(A) BCD and 2421  (B) Gray and Excess-3  (C) 8421 and 2421  (D) 84-2-1 and BCD

✅ **Ans: (B) Gray and Excess-3**

**19.** How many parity bits does a (7,4) Hamming code use?
(A) 2  (B) 3  (C) 4  (D) 7

✅ **Ans: (B) 3**

**20.** Which of these is an alphanumeric code?
(A) BCD  (B) Gray  (C) ASCII  (D) Excess-3

✅ **Ans: (C) ASCII**

---

## D. Boolean Algebra & Logic Gates

**1.** A · A = ?
(A) A  (B) 0  (C) 1  (D) A²

✅ **Ans: (A) A** — (PYQ 2019)

**2.** A + A′ = ?
(A) 0  (B) A  (C) 1  (D) A′

✅ **Ans: (C) 1**

**3.** A · A′ = ?
(A) 0  (B) 1  (C) A  (D) A′

✅ **Ans: (A) 0**

**4.** A + 1 = ?
(A) A  (B) 1  (C) 0  (D) A′

✅ **Ans: (B) 1**

**5.** A + AB = ?
(A) A  (B) B  (C) AB  (D) A + B

✅ **Ans: (A) A** — Absorption

**6.** By De Morgan's theorem, (A + B)′ = ?
(A) A′ + B′  (B) AB  (C) A + B  (D) A′ · B′

✅ **Ans: (D) A′ · B′**

**7.** By De Morgan's theorem, (AB)′ = ?
(A) A′ + B′  (B) A′B′  (C) AB  (D) A + B

✅ **Ans: (A) A′ + B′**

**8.** Which are the universal gates?
(A) AND and OR  (B) NAND and NOR  (C) XOR and XNOR  (D) NOT and AND

✅ **Ans: (B) NAND and NOR**

**9.** An XOR gate outputs 1 when its inputs are:
(A) different  (B) both 0  (C) both 1  (D) always

✅ **Ans: (A) different**

**10.** An XNOR gate outputs 1 when its inputs are:
(A) different  (B) both 0 only  (C) equal  (D) always

✅ **Ans: (C) equal**

**11.** A = 101010, B = 111111. What is (A AND B) OR (A XOR B)?
(A) 111111  (B) 101111  (C) 111010  (D) 101010

✅ **Ans: (A) 111111** — AND = 101010, XOR = 010101, OR of the two = 111111 (PYQ 2025)

**12.** A = 1100, B = 1010. What is A XOR B?
(A) 1110  (B) 0110  (C) 1000  (D) 1001

✅ **Ans: (B) 0110**

**13.** In Boolean algebra, the "+" sign means:
(A) OR  (B) AND  (C) NOT  (D) XOR

✅ **Ans: (A) OR** — (PYQ 2019)

**14.** How many NAND gates are needed to make a NOT gate?
(A) 1  (B) 2  (C) 3  (D) 4

✅ **Ans: (A) 1** — Tie both inputs together

**15.** How many NAND gates are needed to make an AND gate?
(A) 1  (B) 2  (C) 3  (D) 4

✅ **Ans: (B) 2** — NAND followed by a NAND used as NOT

**16.** How many NAND gates are needed to make an OR gate?
(A) 1  (B) 2  (C) 3  (D) 4

✅ **Ans: (C) 3** — Invert each input, then NAND

**17.** What does a 2-input NOR gate output when both inputs are 0?
(A) 0  (B) undefined  (C) A  (D) 1

✅ **Ans: (D) 1**

**18.** A(A + B) = ?
(A) A  (B) B  (C) AB  (D) A + B

✅ **Ans: (A) A**

**19.** A + A′B = ?
(A) A  (B) A + B  (C) AB  (D) B

✅ **Ans: (B) A + B**

**20.** The duality principle swaps:
(A) AND with OR, and 0 with 1  (B) A with B  (C) variables with constants  (D) nothing

✅ **Ans: (A) AND with OR, and 0 with 1**

---

## E. K-Map & Minimization

**1.** How many cells does a 3-variable K-map have?
(A) 4  (B) 8  (C) 16  (D) 6

✅ **Ans: (B) 8**

**2.** How many cells does a 4-variable K-map have?
(A) 8  (B) 12  (C) 16  (D) 32

✅ **Ans: (C) 16**

**3.** Grouping a quad (4 cells) eliminates how many variables?
(A) 2  (B) 1  (C) 3  (D) 4

✅ **Ans: (A) 2**

**4.** Grouping an octet (8 cells) eliminates how many variables?
(A) 1  (B) 2  (C) 3  (D) 4

✅ **Ans: (C) 3**

**5.** Grouping a pair (2 cells) eliminates how many variables?
(A) 1  (B) 2  (C) 3  (D) 0

✅ **Ans: (A) 1**

**6.** K-map rows and columns are ordered in:
(A) binary order  (B) Gray-code order  (C) BCD order  (D) random order

✅ **Ans: (B) Gray-code order**

**7.** Don't-care conditions are input combinations whose output:
(A) is unspecified, so it can be treated as 0 or 1  (B) is always 0  (C) is always 1  (D) causes an error

✅ **Ans: (A) is unspecified, so it can be treated as 0 or 1** — (PYQ 2025)

**8.** F(A,B,C,D) = Σ(0,1,2,3,8,9,10,11). Simplify.
(A) A + B + C + D  (B) AB + CD  (C) A′B  (D) B′

✅ **Ans: (D) B′** — All the minterms have B = 0 (PYQ 2025: correct answer)

**9.** F(A,B,C,D) = Σ(0,1,2,4,5,6,8,9,10,12,13,14). Simplify.
(A) C′ + D′  (B) CD  (C) C + D  (D) A′B′

✅ **Ans: (A) C′ + D′** — Missing 3, 7, 11, 15 = the CD cells (PYQ 2023/2025: correct answer)

**10.** F(A,B,C) = Σ(0,1,2,3). Simplify.
(A) A  (B) B′  (C) A′  (D) 1

✅ **Ans: (C) A′** — All the minterms have A = 0

**11.** F(A,B,C) = Σ(0,1,3,5). What is the minimal SOP?
(A) A + B + C  (B) A′B′ + A′C + B′C  (C) A′B′C  (D) AB + C

✅ **Ans: (B) A′B′ + A′C + B′C** — m0 and m1 → A′B′, m1 and m3 → A′C, m1 and m5 → B′C (PYQ 2025: correct answer)

**12.** F(A,B,C) = Σ(0,1,2,3,5). What is the minimal SOP?
(A) A′ + B′C  (B) A + BC′  (C) A′B′  (D) B + C

✅ **Ans: (A) A′ + B′C** — 0–3 → A′, m1 and m5 → B′C (PYQ 2023/2025: correct answer)

**13.** F(A,B,C) = Σ(1,2,4,6). What is the minimal SOP?
(A) A + B  (B) BC + A′  (C) A′B′C + BC′ + AC′  (D) AB′C

✅ **Ans: (C) A′B′C + BC′ + AC′** — m2 and m6 → BC′, m4 and m6 → AC′, m1 on its own (PYQ 2025)

**14.** SOP stands for:
(A) Sum of Products  (B) Set of Products  (C) Sum of Primes  (D) Series of Pulses

✅ **Ans: (A) Sum of Products**

**15.** A POS expression is implemented with:
(A) AND gates feeding an OR gate  (B) NAND–NAND  (C) NOT then OR  (D) OR gates feeding an AND gate

✅ **Ans: (D) OR gates feeding an AND gate**

**16.** For variables A, B, C, which term is minterm m5?
(A) AB′C  (B) A′BC′  (C) ABC  (D) A′B′C

✅ **Ans: (A) AB′C** — 5 = 101

**17.** For variables A, B, C, which term is maxterm M5?
(A) (A + B′ + C)  (B) (A′ + B + C′)  (C) AB′C  (D) A′BC′

✅ **Ans: (B) (A′ + B + C′)** — For maxterms, a 1 becomes a complemented literal

**18.** F = Σ(0,2,4,5,7) written as a product of maxterms is:
(A) Π(1,3,6)  (B) Π(0,2,4)  (C) Π(5,7)  (D) Π(1,2,3)

✅ **Ans: (A) Π(1,3,6)** — The zeros are at 1, 3 and 6 (PYQ 2025)

**19.** The four corner cells of a 4-variable K-map are:
(A) not adjacent  (B) adjacent only diagonally  (C) adjacent to each other (they can form a quad)  (D) never grouped

✅ **Ans: (C) adjacent to each other (they can form a quad)**

**20.** The Quine–McCluskey method is a:
(A) tabular minimization method  (B) graphical method  (C) coding method  (D) counter design method

✅ **Ans: (A) tabular minimization method**

---

## F. Combinational Circuits & Programmable Logic

**1.** How many inputs does a half adder have?
(A) 2  (B) 3  (C) 1  (D) 4

✅ **Ans: (A) 2**

**2.** How many inputs does a full adder have?
(A) 1  (B) 2  (C) 3  (D) 4

✅ **Ans: (C) 3** — A, B and Cin (PYQ 2025)

**3.** For a half adder, sum and carry are:
(A) Sum = A⊕B, Carry = AB  (B) Sum = AB, Carry = A⊕B  (C) Sum = A + B, Carry = AB  (D) Sum = A′B, Carry = AB′

✅ **Ans: (A) Sum = A⊕B, Carry = AB**

**4.** The sum output of a full adder is:
(A) AB  (B) A⊕B⊕Cin  (C) A + B + Cin  (D) ABCin

✅ **Ans: (B) A⊕B⊕Cin**

**5.** A full adder can be built from:
(A) 2 half adders and 1 OR gate  (B) 2 half adders only  (C) 3 half adders  (D) 1 half adder and 1 AND gate

✅ **Ans: (A) 2 half adders and 1 OR gate**

**6.** What is the main advantage of a carry look-ahead adder?
(A) simpler design  (B) less propagation delay (faster)  (C) lower power  (D) fewer gates

✅ **Ans: (B) less propagation delay (faster)** — (PYQ 2025, twice)

**7.** What is the main drawback of a ripple-carry adder?
(A) carry propagation delay  (B) high cost  (C) it can't add  (D) it needs memory

✅ **Ans: (A) carry propagation delay**

**8.** A multiplexer:
(A) selects one of many inputs and sends it to one output  (B) sends one input to many outputs  (C) only encodes  (D) only compares

✅ **Ans: (A) selects one of many inputs and sends it to one output**

**9.** How many select lines does an 8:1 multiplexer need?
(A) 2  (B) 3  (C) 4  (D) 8

✅ **Ans: (B) 3** — 2³ = 8

**10.** A demultiplexer:
(A) combines many inputs into one  (B) encodes data  (C) compares two numbers  (D) sends one input to one of many outputs

✅ **Ans: (D) sends one input to one of many outputs**

**11.** How many outputs does a 3-to-8 decoder have?
(A) 3  (B) 6  (C) 8  (D) 16

✅ **Ans: (C) 8**

**12.** An encoder converts:
(A) 2ⁿ input lines into an n-bit code  (B) an n-bit code into 2ⁿ outputs  (C) serial data to parallel  (D) analog to digital

✅ **Ans: (A) 2ⁿ input lines into an n-bit code**

**13.** A priority encoder:
(A) compresses data  (B) gives the code of the highest-priority active input  (C) compares numbers  (D) only adds

✅ **Ans: (B) gives the code of the highest-priority active input** — (PYQ 2025)

**14.** A magnitude comparator:
(A) compares two binary numbers  (B) adds them  (C) stores them  (D) counts them

✅ **Ans: (A) compares two binary numbers**

**15.** A PLA has:
(A) programmable AND and programmable OR arrays  (B) fixed AND and fixed OR arrays  (C) only NOT gates  (D) only flip-flops

✅ **Ans: (A) programmable AND and programmable OR arrays** — AND–OR (PYQ 2023, 2025)

**16.** A PAL has:
(A) a fixed AND and programmable OR array  (B) both arrays fixed  (C) a programmable AND and fixed OR array  (D) none of these

✅ **Ans: (C) a programmable AND and fixed OR array**

**17.** A PROM has:
(A) a fixed AND (decoder) and programmable OR array  (B) a programmable AND and fixed OR array  (C) both programmable  (D) neither

✅ **Ans: (A) a fixed AND (decoder) and programmable OR array**

**18.** Which technology gives the most flexibility for implementing digital logic?
(A) ROM  (B) PLA  (C) Gate array  (D) FPGA

✅ **Ans: (D) FPGA** — (PYQ 2025)

**19.** The output of a combinational circuit depends on:
(A) the present inputs only  (B) past inputs only  (C) the clock only  (D) the stored state

✅ **Ans: (A) the present inputs only**

**20.** What is the borrow output of a half subtractor (A − B)?
(A) AB′  (B) A′B  (C) A⊕B  (D) AB

✅ **Ans: (B) A′B** — The difference is A⊕B

---

## G. Sequential Circuits

**1.** The output of a sequential circuit depends on:
(A) the present inputs and the past state (memory)  (B) the present inputs only  (C) nothing  (D) power only

✅ **Ans: (A) the present inputs and the past state (memory)**

**2.** The basic memory element of sequential circuits is the:
(A) gate  (B) flip-flop  (C) multiplexer  (D) decoder

✅ **Ans: (B) flip-flop**

**3.** Which input combination is invalid for an SR (NOR) flip-flop?
(A) S = 0, R = 0  (B) S = 1, R = 0  (C) S = 1, R = 1  (D) S = 0, R = 1

✅ **Ans: (C) S = 1, R = 1**

**4.** A JK flip-flop with J = K = 1:
(A) toggles  (B) sets  (C) resets  (D) holds its state

✅ **Ans: (A) toggles**

**5.** In a D flip-flop, on the clock edge the output:
(A) takes the value of D  (B) toggles  (C) is always 0  (D) holds its state

✅ **Ans: (A) takes the value of D**

**6.** A T flip-flop with T = 1:
(A) holds its state  (B) toggles  (C) resets  (D) sets

✅ **Ans: (B) toggles**

**7.** The race-around problem of the JK flip-flop is removed by using a:
(A) D flip-flop  (B) SR flip-flop  (C) master–slave JK flip-flop  (D) T flip-flop

✅ **Ans: (C) master–slave JK flip-flop**

**8.** How much information does one flip-flop store?
(A) 1 bit  (B) 1 byte  (C) 2 bits  (D) 4 bits

✅ **Ans: (A) 1 bit**

**9.** A register is a:
(A) group of flip-flops that stores a binary word  (B) single gate  (C) decoder  (D) multiplexer

✅ **Ans: (A) group of flip-flops that stores a binary word**

**10.** A shift register:
(A) moves its stored bits left or right  (B) only adds  (C) only counts  (D) only decodes

✅ **Ans: (A) moves its stored bits left or right**

**11.** SIPO stands for:
(A) Single Input, Parallel Output  (B) Serial Input, Partial Output  (C) Series In, Process Out  (D) Serial In, Parallel Out

✅ **Ans: (D) Serial In, Parallel Out**

**12.** A counter made of n flip-flops can have at most how many states?
(A) n  (B) 2ⁿ  (C) 2n  (D) n²

✅ **Ans: (B) 2ⁿ**

**13.** How many flip-flops does a mod-10 (decade) counter need?
(A) 3  (B) 10  (C) 4  (D) 5

✅ **Ans: (C) 4** — 2³ = 8 < 10 ≤ 16 = 2⁴

**14.** A ripple counter is a(n):
(A) asynchronous counter  (B) synchronous counter  (C) ring counter  (D) Johnson counter

✅ **Ans: (A) asynchronous counter**

**15.** In a synchronous counter:
(A) all flip-flops are clocked at the same time  (B) each flip-flop is clocked by the previous one  (C) there is no clock  (D) only the first flip-flop is clocked

✅ **Ans: (A) all flip-flops are clocked at the same time**

**16.** How many states does a ring counter with n flip-flops have?
(A) 2ⁿ  (B) 2n  (C) n²  (D) n

✅ **Ans: (D) n**

**17.** How many states does a Johnson (twisted-ring) counter with n flip-flops have?
(A) n  (B) 2n  (C) 2ⁿ  (D) n − 1

✅ **Ans: (B) 2n**

**18.** How does a latch differ from a flip-flop?
(A) A latch is level-triggered, a flip-flop is edge-triggered  (B) A latch is edge-triggered, a flip-flop is level-triggered  (C) They are identical  (D) A latch has no output

✅ **Ans: (A) A latch is level-triggered, a flip-flop is edge-triggered**

**19.** An edge-triggered flip-flop changes state:
(A) at a clock edge (transition)  (B) for the whole time the clock is high  (C) randomly  (D) never

✅ **Ans: (A) at a clock edge (transition)**

**20.** The accumulator register holds:
(A) the address of the next instruction  (B) a memory address  (C) data during arithmetic and logical operations  (D) status flags only

✅ **Ans: (C) data during arithmetic and logical operations** — (PYQ 2023, 2025)

---

## H. CPU Organization & Addressing Modes

**1.** Where is the ALU located?
(A) In the CPU  (B) In memory  (C) In the input devices  (D) In the output devices

✅ **Ans: (A) In the CPU** — (PYQ 2025)

**2.** A CPU contains:
(A) a card reader and a printer  (B) an analytical engine and a control unit  (C) a control unit and an ALU  (D) an ALU and a card reader

✅ **Ans: (C) a control unit and an ALU** — (PYQ 2020)

**3.** The control unit:
(A) directs and coordinates operations (fetch, decode, execute)  (B) does the arithmetic  (C) stores data permanently  (D) displays output

✅ **Ans: (A) directs and coordinates operations (fetch, decode, execute)** — The ALU acts on its commands (PYQ 2019)

**4.** The program counter (PC) holds the:
(A) current data  (B) address of the next instruction  (C) result  (D) top of the stack

✅ **Ans: (B) address of the next instruction**

**5.** The instruction register (IR) holds the:
(A) instruction currently being executed  (B) next address  (C) data  (D) flags

✅ **Ans: (A) instruction currently being executed**

**6.** The MAR holds the:
(A) data  (B) instruction  (C) flags  (D) address of the memory location to access

✅ **Ans: (D) address of the memory location to access**

**7.** The MDR (MBR) holds the:
(A) data being transferred to or from memory  (B) address  (C) opcode  (D) stack pointer

✅ **Ans: (A) data being transferred to or from memory**

**8.** In which addressing mode is the operand given inside the instruction itself?
(A) Direct  (B) Immediate  (C) Indirect  (D) Indexed

✅ **Ans: (B) Immediate** — (PYQ 2025)

**9.** In direct addressing, the address field contains the:
(A) effective address of the operand  (B) operand itself  (C) address of the address  (D) a register number

✅ **Ans: (A) effective address of the operand**

**10.** In indirect addressing, the address field contains the:
(A) operand itself  (B) a register  (C) address of the location that holds the operand's address  (D) index + base

✅ **Ans: (C) address of the location that holds the operand's address**

**11.** In register addressing, the operand is:
(A) in a CPU register  (B) in memory  (C) in the instruction  (D) on the disk

✅ **Ans: (A) in a CPU register**

**12.** In indexed addressing, the effective address is:
(A) index register + address field  (B) the PC only  (C) the operand itself  (D) the stack top

✅ **Ans: (A) index register + address field**

**13.** The width of the data bus is measured in:
(A) KB  (B) MHz  (C) bits  (D) address lines

✅ **Ans: (C) bits** — (PYQ 2023, 2025)

**14.** How many locations can a 16-line address bus address?
(A) 64 K  (B) 16 K  (C) 32 K  (D) 1 M

✅ **Ans: (A) 64 K** — 2¹⁶ = 65,536

**15.** The address bus is:
(A) bidirectional  (B) unidirectional (CPU → memory)  (C) not used  (D) tri-directional

✅ **Ans: (B) unidirectional (CPU → memory)**

**16.** The data bus is:
(A) bidirectional  (B) unidirectional  (C) not used  (D) only for addresses

✅ **Ans: (A) bidirectional**

**17.** What are the basic steps of the instruction cycle?
(A) Fetch, decode, execute  (B) Load, store, jump  (C) Read, write, print  (D) Input, output, save

✅ **Ans: (A) Fetch, decode, execute**

**18.** The Von Neumann architecture uses:
(A) separate memories for instructions and data  (B) no memory  (C) only cache  (D) one shared memory for both instructions and data

✅ **Ans: (D) one shared memory for both instructions and data**

**19.** The Harvard architecture uses:
(A) one shared memory  (B) separate memories for instructions and data  (C) no I/O  (D) only high speed

✅ **Ans: (B) separate memories for instructions and data** — (PYQ 2025)

**20.** In Flynn's classification, MIMD stands for:
(A) Multiple Instruction, Multiple Data  (B) Multiple Input, Multiple Device  (C) Memory In, Memory Data  (D) Main Instruction, Main Data

✅ **Ans: (A) Multiple Instruction, Multiple Data** — (PYQ 2024 topic)

---

## I. Memory & I/O

**1.** What are the two kinds of main memory?
(A) Primary and secondary  (B) Random and sequential  (C) RAM and ROM  (D) All of these

✅ **Ans: (C) RAM and ROM** — (PYQ 2019)

**2.** RAM is:
(A) volatile  (B) non-volatile  (C) read-only  (D) magnetic

✅ **Ans: (A) volatile**

**3.** ROM is used to store:
(A) permanent data and firmware (e.g. BIOS)  (B) temporary data  (C) the cache  (D) user files

✅ **Ans: (A) permanent data and firmware (e.g. BIOS)** — (PYQ 2023)

**4.** Cache memory sits between the:
(A) disk and RAM  (B) CPU and main memory  (C) keyboard and CPU  (D) ROM and disk

✅ **Ans: (B) CPU and main memory**

**5.** Which is the fastest memory?
(A) CPU registers  (B) Cache  (C) RAM  (D) Hard disk

✅ **Ans: (A) CPU registers**

**6.** Which list is in decreasing order of speed?
(A) Registers > cache > main memory > secondary storage  (B) Cache > registers > disk > RAM  (C) Disk > RAM > cache  (D) RAM > registers > cache

✅ **Ans: (A) Registers > cache > main memory > secondary storage**

**7.** Locality of reference is what makes which memory effective?
(A) Disk  (B) ROM  (C) Cache  (D) The bus

✅ **Ans: (C) Cache**

**8.** The cache hit ratio is:
(A) hits / (hits + misses)  (B) misses / hits  (C) hits × misses  (D) hits − misses

✅ **Ans: (A) hits / (hits + misses)**

**9.** DRAM needs:
(A) periodic refreshing  (B) UV light  (C) no power  (D) a magnet

✅ **Ans: (A) periodic refreshing**

**10.** SRAM is built from:
(A) capacitors  (B) flip-flops (and is faster)  (C) magnetic cores  (D) optical cells

✅ **Ans: (B) flip-flops (and is faster)**

**11.** EEPROM is erased:
(A) electrically  (B) by UV light  (C) by heat  (D) by a magnet

✅ **Ans: (A) electrically**

**12.** EPROM is erased by:
(A) electricity  (B) heat  (C) a magnet  (D) ultraviolet light

✅ **Ans: (D) ultraviolet light**

**13.** Which statement about HDDs and SSDs is true?
(A) An HDD uses spinning platters and an SSD uses flash memory  (B) An HDD is slower  (C) An SSD is more shock-resistant  (D) All of these

✅ **Ans: (D) All of these** — (PYQ 2025)

**14.** A CD-ROM is a(n):
(A) optical memory  (B) semiconductor memory  (C) magnetic memory  (D) memory register

✅ **Ans: (A) optical memory** — (PYQ 2019)

**15.** How much does a high-density, double-sided 3.5" floppy disk hold?
(A) 1.40 MB  (B) 1.44 GB  (C) 1.44 MB  (D) 1.2 GB

✅ **Ans: (C) 1.44 MB** — (PYQ 2020)

**16.** Memory-mapped I/O means:
(A) I/O devices share the memory address space  (B) I/O has a separate address space  (C) the CPU runs faster  (D) there is no I/O

✅ **Ans: (A) I/O devices share the memory address space** — (PYQ 2025)

**17.** DMA lets:
(A) the CPU copy every byte itself  (B) a DMA controller move data directly between I/O and memory  (C) the cache control the disk  (D) the disk control the CPU

✅ **Ans: (B) a DMA controller move data directly between I/O and memory**

**18.** The advantage of interrupt-driven I/O over polling is that:
(A) the CPU doesn't waste time busy-waiting  (B) it needs no hardware  (C) it is always slower  (D) there is no CPU involvement

✅ **Ans: (A) the CPU doesn't waste time busy-waiting**

**19.** Virtual memory uses:
(A) secondary storage as an extension of main memory  (B) only cache  (C) only registers  (D) ROM

✅ **Ans: (A) secondary storage as an extension of main memory**

**20.** A storage area that makes up for the speed difference between devices is a:
(A) memory  (B) accumulator  (C) buffer  (D) address

✅ **Ans: (C) buffer** — (PYQ 2019)

---

## J. Computer Fundamentals, Microprocessors & Logic Families

**1.** Who is called the father of the computer?
(A) Alan Turing  (B) Seymour Cray  (C) Ada Lovelace  (D) Charles Babbage

✅ **Ans: (D) Charles Babbage** — (PYQ 2019)

**2.** Who invented the Difference Engine?
(A) Charles Babbage  (B) Alan Turing  (C) John von Neumann  (D) Blaise Pascal

✅ **Ans: (A) Charles Babbage** — (PYQ 2019)

**3.** First-generation computers used:
(A) transistors  (B) vacuum tubes  (C) ICs  (D) VLSI

✅ **Ans: (B) vacuum tubes** — (PYQ 2019, 2020)

**4.** Second-generation computers used:
(A) transistors  (B) vacuum tubes  (C) ICs  (D) VLSI

✅ **Ans: (A) transistors**

**5.** Third-generation computers used:
(A) vacuum tubes  (B) transistors  (C) ICs (SSI/MSI)  (D) microprocessors

✅ **Ans: (C) ICs (SSI/MSI)** — (PYQ 2019)

**6.** Fourth-generation computers used:
(A) vacuum tubes  (B) transistors  (C) ICs  (D) microprocessors (VLSI)

✅ **Ans: (D) microprocessors (VLSI)** — (PYQ 2019)

**7.** UNIVAC stands for:
(A) Universal Automatic Computer  (B) Universal Array Computer  (C) Unique Automatic Computer  (D) Unvalued Automatic Computer

✅ **Ans: (A) Universal Automatic Computer** — (PYQ 2019)

**8.** ENIAC stands for:
(A) Electronic Numeric Integrated Calculator  (B) Electronic Numerical Integrator and Computer  (C) Electric Number Input Automatic Computer  (D) none of these

✅ **Ans: (B) Electronic Numerical Integrator and Computer**

**9.** Which was the first microprocessor?
(A) Intel 4004  (B) Intel 8085  (C) Intel 8086  (D) Intel 8080

✅ **Ans: (A) Intel 4004** — 1971

**10.** In which year was the Intel 8086 introduced?
(A) 1971  (B) 1974  (C) 1978  (D) 1981

✅ **Ans: (C) 1978** — It wasn't among the PYQ 2025 options

**11.** The Intel 8085 is a(n):
(A) 4-bit microprocessor  (B) 8-bit microprocessor  (C) 16-bit microprocessor  (D) 32-bit microprocessor

✅ **Ans: (B) 8-bit microprocessor** — The 8086 is 16-bit

**12.** A typical use of a microcontroller in cars is:
(A) operating systems  (B) in-flight entertainment  (C) engine control  (D) weather forecasting

✅ **Ans: (C) engine control** — (PYQ 2023, 2025)

**13.** A typical use of a microcontroller in home automation is:
(A) temperature and lighting control  (B) satellite communication  (C) air traffic control  (D) space exploration

✅ **Ans: (A) temperature and lighting control** — (PYQ 2025)

**14.** A hybrid computer:
(A) is purely digital  (B) is purely analog  (C) combines the features of analog and digital computers  (D) none of these

✅ **Ans: (C) combines the features of analog and digital computers** — (PYQ 2019)

**15.** What is the standard supply voltage of the TTL logic family?
(A) 5 V  (B) 12 V  (C) 3.3 V only  (D) −12 V

✅ **Ans: (A) 5 V** — The 2025 key marked "5 V to 12 V"

**16.** Which logic family uses the least power?
(A) TTL  (B) CMOS  (C) ECL  (D) RTL

✅ **Ans: (B) CMOS**

**17.** Which logic family is the fastest?
(A) TTL  (B) CMOS  (C) ECL  (D) DTL

✅ **Ans: (C) ECL** — Emitter-Coupled Logic

**18.** A computer doesn't suffer from tiredness or boredom. This characteristic is called:
(A) accuracy  (B) reliability  (C) versatility  (D) diligence

✅ **Ans: (D) diligence** — (PYQ 2019)

**19.** SMPS stands for:
(A) Switched Mode Power Supply  (B) Start Mode Power Supply  (C) Store Mode Power Supply  (D) Single Mode Power Supply

✅ **Ans: (A) Switched Mode Power Supply** — (PYQ 2020)

**20.** What is called the "brain" of the computer?
(A) ALU  (B) CPU  (C) Memory  (D) Control unit

✅ **Ans: (B) CPU** — (PYQ 2019)

---

### Score tracker

| Topic | Attempt 1 | Attempt 2 |
|---|---|---|
| A. Number systems | /20 | /20 |
| B. Binary arithmetic & complements | /20 | /20 |
| C. Codes | /20 | /20 |
| D. Boolean algebra & gates | /20 | /20 |
| E. K-map & minimization | /20 | /20 |
| F. Combinational & PLDs | /20 | /20 |
| G. Sequential circuits | /20 | /20 |
| H. CPU & addressing modes | /20 | /20 |
| I. Memory & I/O | /20 | /20 |
| J. Fundamentals & microprocessors | /20 | /20 |
| **Total** | **/200** | **/200** |
