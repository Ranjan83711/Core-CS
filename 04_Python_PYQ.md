# Bihar STET Paper 2 (Computer Science): Python PYQ Bank

**Papers covered:** the same 8 papers as the earlier chapters.

| Year | Paper | Python questions | Other programming questions |
|---|---|---|---|
| 2019 | Second sitting | 0 | 3 (C/C++ basics) |
| 2020 | Re-exam | 0 | 10 (C++ basics) |
| 2023 | 12 Sep, Shift 1 | 0 | — |
| 2024 | 11 Jun (memory-based) | 0 | — |
| 2025 | 3 Nov Shift 1 | 7 | |
| 2025 | 3 Nov Shift 2 | 7 | |
| 2025 | 4 Nov Shift 2 | 4 | |
| 2025 | 7 Nov Shift 1 | 4 | |
| **Total** | | **22** | **13** |

> **Python first appeared in 2025, and in a big way: 4–7 questions per shift.** The style is the **CBSE Class 11–12 Computer Science (083)** syllabus, word-for-word in places. Expect:
> - **Code-output questions** (strings, lists, dicts, functions/`global`, try/finally, file read).
> - **Theory one-liners** (identifiers, the `is` operator, mapped type, `collections`, pandas DataFrame and `head()`).
>
> Before 2025 the programming questions were C/C++ basics. They're listed in the appendix.

**Notes on answers**
- I traced the output questions by hand. Python isn't installed on this PC, so none of them were run.
- Some questions have **typos in the official paper**. The answer given is the one the examiner intended, and each typo is noted.

---

## 1. Topic frequency (2025)

| Rank | Topic | Times asked |
|---|---|---|
| 1 | **Code output** (strings ×3, list, dict ×2, operator precedence ×2, functions/`global` ×2, try/finally, file read) | 12 |
| 2 | **Basics** (identifier, `is` operator, mapped type, object ID) | 4 |
| 3 | **Data structures in Python** (list for a queue, deque via `collections`, deque concept) | 3 |
| 4 | **Pandas** (DataFrame, `head(n)`) | 2 |
| 5 | **Exception handling, theory** (advantage) | 1 |

---

## 2. Questions with answers and working

### A. Output questions (the most important group)
| # | Code / question (paraphrased) | Answer | Working | Paper |
|---|---|---|---|---|
| 1 | `"Paralympic Games".split("m")` | **['Paraly', 'pic Ga', 'es']** | The separator "m" is removed, leaving 3 parts. (The paper wrote `Split` with a capital S, which is a typo.) | 3 Nov S1 |
| 2 | `game="olympic2024"; print(game.index("C"))` | **ValueError** | Uppercase "C" isn't in the string. `index()` raises an error, while `find()` would return −1. | 4 Nov |
| 3 | `S="an apple. a toy."; find('a', 2)` | **3** (intended) | Searching from index 2, the next 'a' is at index 3. The paper has typos (`'a '` and `S`/`s`). | 7 Nov |
| 4 | `L=['TIC','TAC']; print(L[::-1])` | **['TAC', 'TIC']** | It reverses the list, not the strings. | 4 Nov |
| 5 | `D={'S01':95,'S02':96}` and `for I in D: print(I, end='#')` | **S01#S02#** | Looping over a dict gives its **keys**. | 3 Nov S2 |
| 6 | `print(14%3**2*4)` | **20** | `**` first: 3²=9. Then `%` and `*` left to right: 14%9=5, 5×4=20. | 3 Nov S2 |
| 7 | `def Change(N): N=N+10; print(N,end='$$')`, then `N=15; Change(N); print(N)` | **25$$15** | The function changes its local copy only. | 3 Nov S1 |
| 8 | `a=5`, then `def func_1(b=10): global a; a=b-10; b+=a; print(a,b)`, then `func_1(a)` | **-5 0** | b=5. Then a=5−10=−5, and b=5+(−5)=0. | 4 Nov |
| 9 | `N='5'`, then try `print('WORD '+N, end='#')`, except `print('ERROR')`, finally `print('OVER')` | **WORD 5#OVER** | No exception happens, and `finally` always runs. | 7 Nov |
| 10 | File holds "Life goes on as it never ends". `s1=read(5)`, `s2=readline(4)`, `s3=read(3)`, `print(s1,s3,sep="#")` | **Life # on** | s1="Life ", s2="goes", s3=" on" | 3 Nov S1 |
| 12 | `3 + 3.00, 3**3.0` | **(6.0, 27.0)** | Comma-separated values form a tuple. Any float operand makes the result a float. | 3 Nov S2 |
| 11 | `D1={1:'a',2:'b'}`: which statement causes an error? (get(1), get(3), del(1), clear(1)) | **D1.del(1)** | `del` is a statement, not a method. (`clear(1)` would also fail, because clear takes no argument, but the intended answer is `del`.) | 4 Nov |

### B. Basics & operators
| # | Asked | Answer | Paper |
|---|---|---|---|
| 1 | Operator that is True when both variables point to the same memory location | **is** | 3 Nov S1 |
| 2 | Valid identifier (global, Break, def, with) | **Break** (Python is case-sensitive, so `Break` is not the keyword `break`) | 3 Nov S1 |
| 3 | Mapped data type | **Dictionary** | 3 Nov S2 |
| 4 | A: every object has a unique ID. R: the ID stays the same for the object's lifetime. | **Both true.** The logically correct choice is that R does **not** explain A, but some answer keys give "R explains A", so read the options carefully. | 3 Nov S2 |

### C. Data structures in Python
| # | Asked | Answer | Paper |
|---|---|---|---|
| 1 | Data type used to implement a queue | **List** | 3 Nov S1 |
| 2 | Module to import for a double-ended queue | **collections** (`collections.deque`) | 3 Nov S2 |
| 3 | Queue with insertion and deletion at both ends | **Deque (double-ended queue)** | 7 Nov |

### D. Exceptions
| # | Asked | Answer | Paper |
|---|---|---|---|
| 1 | Main advantage of exception handling | **It handles unexpected errors and allows graceful termination** | 7 Nov |

### E. Pandas
| # | Asked | Answer | Paper |
|---|---|---|---|
| 1 | 2-D Python data structure with row and column index | **DataFrame** (Series is 1-D) | 3 Nov S1 |
| 2 | Function that returns the first n rows of a DataFrame | **head(n)** | 3 Nov S2 |

---

## 3. Appendix: C/C++ programming basics (2019 & 2020)

| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Variables accessible by all modules | **Global** | 2019 |
| 2 | Variables accessible only inside a module | **Local** | 2020 |
| 3 | Stack, queue and linked list can be implemented using | **Arrays** | 2019 |
| 4 | math.h is a | **Header file** | 2019 |
| 5 | Header file for I/O in C++ | **<iostream.h>** | 2020 |
| 6 | C++ keywords are also called | **Reserved words** | 2020 |
| 7 | Which of `* / %` has the highest precedence? | **All have the same precedence** | 2020 |
| 8 | Basic data type (Array, Struct, Boolean, Int) | **int** | 2020 |
| 9 | To store text we need a | **String variable** | 2020 |
| 10 | `>=` is a(n) | **Operator** | 2020 |
| 11 | `int A=10; A++; cout<<A;` | **11** | 2020 |
| 12 | `float` is a | **Data type** | 2020 |
| 13 | Which is an abstract data type? (class, double, int, string) | **class** | 2020 |

---

## 4. Must-revise checklist (CBSE 083 style)

1. **Tokens:** keywords (case-sensitive), identifier rules, literals, operators. `is` vs `==`, `in`, `//`, `%`, `**` (right-associative), precedence.
2. **Data types:** mutable (list, dict, set) vs immutable (int, float, str, tuple); `type()`, `id()`; dictionary = mapping type.
3. **Strings:** slicing (`[::-1]`), `split`, `join`, `find` (returns −1) vs `index` (raises ValueError), `count`, `upper`/`lower`/`title`/`capitalize`, `strip`, `replace`, `isdigit`/`isalpha`.
4. **Lists/tuples:** `append` vs `extend` vs `insert`, `pop`/`remove`, `sort()` (returns None) vs `sorted()`, slicing, aliasing (`M = L`), one-element tuple `(5,)`.
5. **Dictionaries:** looping gives keys, `get()` returns None, `d[k]` raises KeyError, `keys`/`values`/`items`/`pop`/`update`/`clear`, keys must be immutable.
6. **Functions:** default arguments, local vs `global`, LEGB scope, return None, `*args`, lambda, recursion.
7. **Exceptions:** try/except/else/finally flow (finally always runs), common errors (ValueError, TypeError, NameError, IndexError, KeyError, ZeroDivisionError).
8. **File handling:** modes r/w/a/rb/wb, `read(n)`, `readline()`, `readlines()`, `seek`/`tell`, `with`, pickle (dump/load), csv (writer/reader).
9. **Stack/queue:** list with `append`/`pop`, `pop(0)` for a queue, `collections.deque` (`appendleft`/`popleft`), overflow/underflow, postfix evaluation.
10. **Pandas/NumPy:** Series (1-D) vs DataFrame (2-D), `head`/`tail` (default 5), `shape`, `loc`/`iloc`, `read_csv`/`to_csv`, NaN.

Practice set: `04b_Python_Practice_MCQs.md`
