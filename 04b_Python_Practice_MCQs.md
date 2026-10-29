# Python: Practice MCQs (200 questions)

**Bihar STET Paper 2 (Computer Science)**

There are 10 topics with 20 questions each, in the CBSE Class 11–12 (083) style used by the 2025 papers. The answer is shown right under each question, so you can revise in one read. Target: 17/20 or better.

For output questions, **trace the code on paper** before you look at the options. That's how you'll do it in the exam.

---

## A. Python Basics, Tokens & Data Types

**1.** Who developed Python?
(A) Guido van Rossum  (B) Dennis Ritchie  (C) James Gosling  (D) Bjarne Stroustrup

✅ **Ans: (A) Guido van Rossum** — 1991

**2.** Python is a(n):
(A) compiled, low-level language  (B) interpreted, high-level language  (C) assembly language  (D) machine language

✅ **Ans: (B) interpreted, high-level language**

**3.** Which is a valid identifier?
(A) `2name`  (B) `my-var`  (C) `_total`  (D) `for`

✅ **Ans: (C) `_total`** — Can't start with a digit, can't contain `-`, can't be a keyword

**4.** Which of these is a Python keyword?
(A) `Break`  (B) `global`  (C) `Main`  (D) `value`

✅ **Ans: (B) `global`**

**5.** In Python, `Break` (capital B) is:
(A) a keyword  (B) a valid identifier  (C) a syntax error  (D) an operator

✅ **Ans: (B) a valid identifier** — Case-sensitive (PYQ 2025)

**6.** What does `type(3.0)` return?
(A) int  (B) str  (C) complex  (D) float

✅ **Ans: (D) float**

**7.** What does `type(5j)` return?
(A) complex  (B) int  (C) float  (D) str

✅ **Ans: (A) complex**

**8.** Which data type is immutable?
(A) list  (B) dict  (C) set  (D) tuple

✅ **Ans: (D) tuple** — str, int and float are also immutable

**9.** Which data type is mutable?
(A) str  (B) tuple  (C) list  (D) int

✅ **Ans: (C) list**

**10.** What does `bool(0)` return?
(A) True  (B) False  (C) 0  (D) an error

✅ **Ans: (B) False** — 0, "", [], {} and None are all falsy

**11.** Which expression converts the string "25" to an integer?
(A) `int("25")`  (B) `str(25)`  (C) `float("25")`  (D) `chr(25)`

✅ **Ans: (A) `int("25")`**

**12.** What type does `input()` return?
(A) int  (B) float  (C) str  (D) it depends on what is typed

✅ **Ans: (C) str** — Always a string

**13.** Which symbol starts a single-line comment?
(A) `#`  (B) `//`  (C) `/*`  (D) `--`

✅ **Ans: (A) `#`**

**14.** After `a, b = 1, 2` and then `a, b = b, a`:
(A) both are 1  (B) a = 2 and b = 1  (C) an error occurs  (D) a = 1 and b = 2

✅ **Ans: (B) a = 2 and b = 1** — Swaps the values

**15.** In Python, indentation is used to:
(A) define blocks of code  (B) write comments  (C) do nothing  (D) speed up the program

✅ **Ans: (A) define blocks of code**

**16.** `None` in Python stands for:
(A) 0  (B) the string "False"  (C) an empty list `[]`  (D) the absence of a value (NoneType)

✅ **Ans: (D) the absence of a value (NoneType)**

**17.** `id(x)` returns:
(A) the unique identity of the object  (B) its type  (C) its size  (D) its value

✅ **Ans: (A) the unique identity of the object** — Fixed for the object's lifetime (PYQ 2025 A-R)

**18.** What does `print(type([]))` show?
(A) `<class 'tuple'>`  (B) `<class 'dict'>`  (C) `<class 'list'>`  (D) `<class 'set'>`

✅ **Ans: (C) `<class 'list'>`**

**19.** What is the extension of a Python source file?
(A) `.py`  (B) `.pt`  (C) `.pyt`  (D) `.p`

✅ **Ans: (A) `.py`**

**20.** What is the prompt in Python's interactive mode?
(A) `$`  (B) `>>>`  (C) `#`  (D) `%`

✅ **Ans: (B) `>>>`**

---

## B. Operators & Expressions

**1.** `print(7 // 2)`
(A) 3.5  (B) 3  (C) 4  (D) 3.0

✅ **Ans: (B) 3** — Floor division

**2.** `print(7 % 3)`
(A) 1  (B) 2  (C) 0  (D) 2.33

✅ **Ans: (A) 1**

**3.** `print(2 ** 3 ** 2)`
(A) 64  (B) 512  (C) 36  (D) 81

✅ **Ans: (B) 512** — `**` is right-associative: 3²=9, then 2⁹=512

**4.** `print(14 % 3 ** 2 * 4)`
(A) 16  (B) 64  (C) 20  (D) 256

✅ **Ans: (C) 20** — 3²=9, 14%9=5, 5×4=20 (PYQ 2025)

**5.** `print(10 / 4)`
(A) 2  (B) 2.5  (C) 2.0  (D) 3

✅ **Ans: (B) 2.5** — `/` always gives a float

**6.** `print(-7 // 2)`
(A) -3  (B) -3.5  (C) 3  (D) -4

✅ **Ans: (D) -4** — Floors toward −∞

**7.** Which operator is True when two variables refer to the same object in memory?
(A) `==`  (B) `is`  (C) `in`  (D) `=`

✅ **Ans: (B) `is`** — (PYQ 2025)

**8.** `print('a' in 'apple')`
(A) True  (B) False  (C) 1  (D) an error

✅ **Ans: (A) True**

**9.** `print(not True or True)`
(A) True  (B) False  (C) None  (D) an error

✅ **Ans: (A) True** — (not True)=False, then False or True = True

**10.** Which operator has the highest precedence?
(A) `**`  (B) `*`  (C) `+`  (D) `and`

✅ **Ans: (A) `**`**

**11.** `print(5 > 3 and 2 > 4)`
(A) True  (B) False  (C) 1  (D) an error

✅ **Ans: (B) False**

**12.** `print(3 + 4 * 2)`
(A) 14  (B) 10  (C) 11  (D) 24

✅ **Ans: (C) 11**

**13.** `x = 5; x += 3; x *= 2; print(x)`
(A) 16  (B) 13  (C) 11  (D) 10

✅ **Ans: (A) 16** — (5+3)×2

**14.** `print(10 == 10.0)`
(A) True  (B) False  (C) an error  (D) None

✅ **Ans: (A) True**

**15.** `print(5 & 3)`
(A) 7  (B) 6  (C) 8  (D) 1

✅ **Ans: (D) 1** — 101 & 011 = 001

**16.** `print(5 | 3)`
(A) 1  (B) 7  (C) 6  (D) 8

✅ **Ans: (B) 7** — 101 | 011 = 111

**17.** `print(5 ^ 3)`
(A) 1  (B) 7  (C) 6  (D) 8

✅ **Ans: (C) 6** — 101 ^ 011 = 110

**18.** `print(2 << 2)`
(A) 4  (B) 8  (C) 1  (D) 16

✅ **Ans: (B) 8** — 2×2²

**19.** `print("ab" * 3)`
(A) ababab  (B) ab3  (C) an error  (D) aaabbb

✅ **Ans: (A) ababab**

**20.** `print(17 % -5)`
(A) 2  (B) 3  (C) -2  (D) -3

✅ **Ans: (D) -3** — The result takes the sign of the divisor: 17 = (−5)(−4) + (−3)

---

## C. Strings

**1.** `s = "Paralympic Games"; print(s.split("m"))`
(A) `['Paraly','m','pic Ga','m','es']`  (B) `('Paraly','pic Ga','es')`  (C) `['Paralympic','Games']`  (D) `['Paraly','pic Ga','es']`

✅ **Ans: (D) `['Paraly','pic Ga','es']`** — The separator is removed (PYQ 2025)

**2.** `print("olympic2024".index("C"))`
(A) ValueError  (B) 6  (C) -1  (D) 0

✅ **Ans: (A) ValueError** — `index()` raises an error when the text isn't found (PYQ 2025)

**3.** `print("olympic2024".find("C"))`
(A) ValueError  (B) 6  (C) -1  (D) 0

✅ **Ans: (C) -1** — `find()` returns −1

**4.** `print("an apple".find('a', 2))`
(A) 0  (B) 3  (C) 1  (D) -1

✅ **Ans: (B) 3** — Searching from index 2, the next 'a' is at index 3 (PYQ 2025 pattern)

**5.** `s = "COMPUTER"; print(s[2:5])`
(A) MPU  (B) OMP  (C) MPUT  (D) PUT

✅ **Ans: (A) MPU** — Indexes 2, 3, 4

**6.** `print("PYTHON"[-1])`
(A) P  (B) N  (C) O  (D) an error

✅ **Ans: (B) N**

**7.** `print("STET"[::-1])`
(A) STET  (B) TEST  (C) TETS  (D) ETST

✅ **Ans: (C) TETS**

**8.** `print(len("Bihar STET"))`
(A) 9  (B) 10  (C) 11  (D) 8

✅ **Ans: (B) 10** — The space counts

**9.** `print("hello".upper())`
(A) HELLO  (B) Hello  (C) hello  (D) hELLO

✅ **Ans: (A) HELLO**

**10.** `print("Hello World".count("o"))`
(A) 1  (B) 3  (C) 0  (D) 2

✅ **Ans: (D) 2**

**11.** Strings in Python are:
(A) immutable  (B) mutable  (C) sometimes mutable  (D) none of these

✅ **Ans: (A) immutable**

**12.** `s = "abc"; s[0] = "z"`
(A) s becomes "zbc"  (B) s becomes "abz"  (C) TypeError  (D) None

✅ **Ans: (C) TypeError**

**13.** `print("  hi  ".strip())`
(A) `hi`  (B) `  hi`  (C) `hi  `  (D) `  hi  `

✅ **Ans: (A) `hi`**

**14.** `print("-".join(["a","b","c"]))`
(A) abc  (B) a-b-c  (C) -a-b-c-  (D) ['a','b','c']

✅ **Ans: (B) a-b-c**

**15.** `print("hello world".title())`
(A) Hello world  (B) HELLO WORLD  (C) Hello World  (D) hello World

✅ **Ans: (C) Hello World**

**16.** `print("abc" + "def")`
(A) abcdef  (B) abc def  (C) an error  (D) abc+def

✅ **Ans: (A) abcdef**

**17.** `print("a,b,,c".split(","))`
(A) `['a','b','c']`  (B) `['a','b','','c']`  (C) `['a,b,,c']`  (D) an error

✅ **Ans: (B) `['a','b','','c']`**

**18.** `print("Python"[1:4])`
(A) Pyt  (B) ytho  (C) yth  (D) tho

✅ **Ans: (C) yth** — Indexes 1, 2, 3

**19.** `print("STET".lower() == "stet")`
(A) True  (B) False  (C) stet  (D) an error

✅ **Ans: (A) True**

**20.** Which method checks whether every character in a string is a digit?
(A) `isalpha()`  (B) `isnum()`  (C) `digit()`  (D) `isdigit()`

✅ **Ans: (D) `isdigit()`**

---

## D. Lists & Tuples

**1.** `L = ['TIC','TAC']; print(L[::-1])`
(A) `['CIT','CAT']`  (B) `['TIC','TAC']`  (C) `['CAT','CIT']`  (D) `['TAC','TIC']`

✅ **Ans: (D) `['TAC','TIC']`** — Reverses the order of the elements (PYQ 2025)

**2.** Which data type is normally used to implement a stack or queue in Python?
(A) list  (B) set  (C) dict  (D) tuple

✅ **Ans: (A) list** — (PYQ 2025)

**3.** `L = [1,2,3]; L.append([4,5]); print(len(L))`
(A) 5  (B) 4  (C) 3  (D) an error

✅ **Ans: (B) 4** — The whole list is added as one element

**4.** `L = [1,2,3]; L.extend([4,5]); print(len(L))`
(A) 5  (B) 4  (C) 3  (D) an error

✅ **Ans: (A) 5**

**5.** `L = [10,20,30]; L.insert(1,15); print(L)`
(A) `[15,10,20,30]`  (B) `[10,20,15,30]`  (C) `[10,15,20,30]`  (D) an error

✅ **Ans: (C) `[10,15,20,30]`**

**6.** `L.pop()` with no argument removes:
(A) the last element  (B) the first element  (C) all elements  (D) a random element

✅ **Ans: (A) the last element**

**7.** `print([3,1,2].sort())`
(A) `[1,2,3]`  (B) None  (C) `[3,2,1]`  (D) an error

✅ **Ans: (B) None** — `sort()` sorts in place and returns None

**8.** `print(sorted([3,1,2]))`
(A) None  (B) `[3,1,2]`  (C) `[3,2,1]`  (D) `[1,2,3]`

✅ **Ans: (D) `[1,2,3]`** — Returns a new list

**9.** `L = [1,2,3,4,5]; print(L[1:4])`
(A) `[1,2,3]`  (B) `[2,3,4]`  (C) `[2,3,4,5]`  (D) `[1,2,3,4]`

✅ **Ans: (B) `[2,3,4]`**

**10.** `print([1,2] * 2)`
(A) `[1,2,1,2]`  (B) `[2,4]`  (C) `[[1,2],[1,2]]`  (D) an error

✅ **Ans: (A) `[1,2,1,2]`**

**11.** How do you write a tuple with a single element?
(A) `(5)`  (B) `(5,)`  (C) `[5]`  (D) `{5}`

✅ **Ans: (B) `(5,)`**

**12.** `T = (1,2,3); T[0] = 10`
(A) T becomes (10,2,3)  (B) T stays (1,2,3) silently  (C) TypeError  (D) None

✅ **Ans: (C) TypeError** — Tuples are immutable

**13.** `L = [1,2,3]; M = L; M.append(4); print(L)`
(A) `[1,2,3]`  (B) `[1,2,3,4]`  (C) an error  (D) `[4]`

✅ **Ans: (B) `[1,2,3,4]`** — M is an alias of L

**14.** `print(max([4,9,2]))`
(A) 9  (B) 4  (C) 2  (D) 15

✅ **Ans: (A) 9**

**15.** `print([1,2,3,2].count(2))`
(A) 1  (B) 3  (C) 4  (D) 2

✅ **Ans: (D) 2**

**16.** `print([10,20,30].index(30))`
(A) 2  (B) 3  (C) 1  (D) 0

✅ **Ans: (A) 2**

**17.** `print([x*x for x in range(4)])`
(A) `[1,4,9,16]`  (B) `[0,1,4,9]`  (C) `[0,1,2,3]`  (D) `[0,2,4,6]`

✅ **Ans: (B) `[0,1,4,9]`**

**18.** `L.remove(x)` deletes:
(A) the first occurrence of the value x  (B) the element at index x  (C) every occurrence of x  (D) the last element

✅ **Ans: (A) the first occurrence of the value x**

**19.** `print((1,2,3) + (4,))`
(A) an error  (B) `(1,2,3,(4,))`  (C) `(1,2,3,4)`  (D) `[1,2,3,4]`

✅ **Ans: (C) `(1,2,3,4)`**

**20.** `L = [[1,2],[3,4]]; print(L[1][0])`
(A) 2  (B) 1  (C) 4  (D) 3

✅ **Ans: (D) 3**

---

## E. Dictionaries & Sets

**1.** Which is a mapped (mapping) data type?
(A) list  (B) set  (C) dictionary  (D) bool

✅ **Ans: (C) dictionary** — (PYQ 2025)

**2.** `D = {'S01':95, 'S02':96}` followed by `for k in D: print(k, end='#')`
(A) `S01#S02#`  (B) `95#96#`  (C) `S01,95#S02,96#`  (D) `S01#95#S02#96#`

✅ **Ans: (A) `S01#S02#`** — Looping gives the keys (PYQ 2025)

**3.** `D1 = {1:'a', 2:'b'}`. Which statement causes an error?
(A) `D1.get(1)`  (B) `D1.get(3)`  (C) `D1.del(1)`  (D) `D1.keys()`

✅ **Ans: (C) `D1.del(1)`** — `del D1[1]` is the correct syntax (PYQ 2025)

**4.** For the same D1, what does `D1.get(3)` return?
(A) KeyError  (B) None  (C) 0  (D) ''

✅ **Ans: (B) None**

**5.** For the same D1, what does `D1[3]` give?
(A) None  (B) 0  (C) ''  (D) KeyError

✅ **Ans: (D) KeyError**

**6.** Dictionary keys must be:
(A) immutable (hashable)  (B) mutable  (C) lists  (D) anything at all

✅ **Ans: (A) immutable (hashable)**

**7.** Which of these cannot be a dictionary key?
(A) a tuple  (B) an int  (C) a list  (D) a str

✅ **Ans: (C) a list**

**8.** `d = {'a':1}; d['b'] = 2; print(len(d))`
(A) 1  (B) 2  (C) 3  (D) an error

✅ **Ans: (B) 2**

**9.** `d.items()` returns the dictionary's:
(A) key–value pairs  (B) keys only  (C) values only  (D) length

✅ **Ans: (A) key–value pairs**

**10.** `d = {'a':1,'b':2}; print(d.pop('a'))`
(A) 'a'  (B) 1  (C) {'b':2}  (D) None

✅ **Ans: (B) 1**

**11.** A set is:
(A) an unordered collection of unique elements  (B) an ordered collection that allows duplicates  (C) a key–value store  (D) immutable

✅ **Ans: (A) an unordered collection of unique elements**

**12.** `print(len({1,2,2,3}))`
(A) 4  (B) 2  (C) 3  (D) an error

✅ **Ans: (C) 3**

**13.** `print({1,2,3} & {2,3,4})`
(A) `{2,3}`  (B) `{1,2,3,4}`  (C) `{1,4}`  (D) `set()`

✅ **Ans: (A) `{2,3}`** — Intersection

**14.** `print({1,2,3} | {3,4})`
(A) `{3}`  (B) `{1,2,3,4}`  (C) `{1,2}`  (D) `{4}`

✅ **Ans: (B) `{1,2,3,4}`** — Union

**15.** `print({1,2,3} - {2})`
(A) `{2}`  (B) `{1,2,3}`  (C) `set()`  (D) `{1,3}`

✅ **Ans: (D) `{1,3}`** — Difference

**16.** How do you create an empty set?
(A) `set()`  (B) `{}`  (C) `[]`  (D) `()`

✅ **Ans: (A) `set()`** — `{}` is an empty dict

**17.** `print(type({}))`
(A) set  (B) dict  (C) list  (D) tuple

✅ **Ans: (B) dict**

**18.** From Python 3.7 onwards, a dictionary keeps its items in:
(A) insertion order  (B) sorted order  (C) random order  (D) reverse order

✅ **Ans: (A) insertion order**

**19.** `print(dict(zip(['a','b'],[1,2])))`
(A) `[('a',1),('b',2)]`  (B) `{'a':'b',1:2}`  (C) `{'a':1,'b':2}`  (D) an error

✅ **Ans: (C) `{'a':1,'b':2}`**

**20.** `print({'x':1, 'x':2})`
(A) `{'x':1}`  (B) `{'x':2}`  (C) an error  (D) `{'x':[1,2]}`

✅ **Ans: (B) `{'x':2}`** — The last value wins

---

## F. Control Flow & Functions

**1.** `print(list(range(1,10,3)))`
(A) `[1,4,7]`  (B) `[1,4,7,10]`  (C) `[1,3,5,7,9]`  (D) `[3,6,9]`

✅ **Ans: (A) `[1,4,7]`** — Stops before 10

**2.** `print(list(range(5)))`
(A) `[1,2,3,4,5]`  (B) `[0,1,2,3,4]`  (C) `[0,1,2,3,4,5]`  (D) `[5]`

✅ **Ans: (B) `[0,1,2,3,4]`**

**3.** `for i in range(3): print(i, end=' ')`
(A) `0 1 2 3`  (B) `1 2 3`  (C) `0 1 2`  (D) `3`

✅ **Ans: (C) `0 1 2`**

**4.** `break` inside a loop:
(A) exits the loop immediately  (B) skips the current iteration  (C) does nothing  (D) restarts the loop

✅ **Ans: (A) exits the loop immediately**

**5.** `continue` inside a loop:
(A) exits the loop  (B) skips the rest of the current iteration and moves to the next  (C) ends the program  (D) is the same as `pass`

✅ **Ans: (B) skips the rest of the current iteration and moves to the next**

**6.** `pass` is:
(A) a loop exit  (B) an iteration skip  (C) an error  (D) a null statement that does nothing (a placeholder)

✅ **Ans: (D) a null statement that does nothing (a placeholder)**

**7.** The `else` block of a `while` loop runs when:
(A) the loop ends normally, without `break`  (B) always  (C) only after `break`  (D) never

✅ **Ans: (A) the loop ends normally, without `break`**

**8.** What is the output?
```python
def Change(N):
    N = N + 10
    print(N, end='$$')
N = 15
Change(N)
print(N)
```
(A) `25$$15`  (B) `15$$25`  (C) `25$$25`  (D) `2525$$`

✅ **Ans: (A) `25$$15`** — Only the local N changes (PYQ 2025)

**9.** What is the output?
```python
a = 5
def func_1(b=10):
    global a
    a = b - 10
    b += a
    print(a, b)
func_1(a)
```
(A) `0 5`  (B) `5 0`  (C) `0 -5`  (D) `-5 0`

✅ **Ans: (D) `-5 0`** — a = 5 − 10 = −5. b = 5 + (−5) = 0 (PYQ 2025)

**10.** Which keyword defines a function?
(A) `def`  (B) `function`  (C) `func`  (D) `define`

✅ **Ans: (A) `def`**

**11.** A function with no `return` statement returns:
(A) 0  (B) ""  (C) None  (D) an error

✅ **Ans: (C) None**

**12.** `def f(a, b=2): return a*b` followed by `print(f(3))`
(A) 6  (B) 3  (C) 5  (D) an error

✅ **Ans: (A) 6**

**13.** Parameters with default values must come:
(A) before the non-default parameters  (B) after the non-default parameters  (C) anywhere  (D) they are not allowed

✅ **Ans: (B) after the non-default parameters**

**14.** A variable created inside a function is:
(A) local  (B) global  (C) static  (D) built-in

✅ **Ans: (A) local**

**15.** In what order does Python look up a name (the LEGB rule)?
(A) Local → Enclosing → Global → Built-in  (B) Global → Local → Built-in → Enclosing  (C) Built-in → Global → Local  (D) random

✅ **Ans: (A) Local → Enclosing → Global → Built-in**

**16.** `f = lambda x: x*2; print(f(5))`
(A) 25  (B) 7  (C) an error  (D) 10

✅ **Ans: (D) 10**

**17.** Recursive function calls are managed using a:
(A) stack  (B) queue  (C) heap only  (D) none of these

✅ **Ans: (A) stack**

**18.** `def f(*args): return len(args)` followed by `print(f(1,2,3))`
(A) 1  (B) 3  (C) 6  (D) an error

✅ **Ans: (B) 3**

**19.** `x = 10`, then `def f(): print(x)`, then `f()`
(A) an error  (B) None  (C) 10  (D) 0

✅ **Ans: (C) 10** — Global variables can be read without `global`

**20.** The body of a function runs when the function is:
(A) called  (B) defined  (C) only imported  (D) never

✅ **Ans: (A) called**

---

## G. Exception Handling & File Handling

**1.** What is the output?
```python
N = '5'
try:
    print('WORD ' + N, end='#')
except:
    print('ERROR', end='#')
finally:
    print('OVER')
```
(A) `ERROR#`  (B) `WORD 5#OVER`  (C) `WORD 5#`  (D) `ERROR#OVER`

✅ **Ans: (B) `WORD 5#OVER`** — There's no error, and `finally` always runs (PYQ 2025)

**2.** The `finally` block:
(A) always runs  (B) runs only when there is an error  (C) runs only when there is no error  (D) never runs

✅ **Ans: (A) always runs**

**3.** `int("abc")` raises:
(A) TypeError  (B) NameError  (C) ValueError  (D) KeyError

✅ **Ans: (C) ValueError**

**4.** `1/0` raises:
(A) ValueError  (B) TypeError  (C) IndexError  (D) ZeroDivisionError

✅ **Ans: (D) ZeroDivisionError**

**5.** `[1,2][5]` raises:
(A) IndexError  (B) KeyError  (C) ValueError  (D) TypeError

✅ **Ans: (A) IndexError**

**6.** `"5" + 5` raises:
(A) ValueError  (B) TypeError  (C) NameError  (D) no error

✅ **Ans: (B) TypeError**

**7.** Using a variable that was never defined raises:
(A) NameError  (B) ValueError  (C) KeyError  (D) TypeError

✅ **Ans: (A) NameError**

**8.** What is the main advantage of exception handling?
(A) It stops code from running  (B) It improves readability  (C) It handles unexpected errors and allows the program to end gracefully  (D) It removes the need for classes

✅ **Ans: (C) It handles unexpected errors and allows the program to end gracefully** — (PYQ 2025)

**9.** Which keyword raises an exception yourself?
(A) `raise`  (B) `throw`  (C) `except`  (D) `error`

✅ **Ans: (A) `raise`**

**10.** `open("f.txt", "w")`:
(A) creates the file, or empties it if it exists, for writing  (B) appends to the file  (C) opens it for reading  (D) gives an error if the file exists

✅ **Ans: (A) creates the file, or empties it if it exists, for writing**

**11.** File mode `"a"` means:
(A) read  (B) append  (C) write (overwrite)  (D) binary

✅ **Ans: (B) append**

**12.** What is the default mode of `open()`?
(A) `'r'` (read, text)  (B) `'w'`  (C) `'a'`  (D) `'rb'`

✅ **Ans: (A) `'r'` (read, text)**

**13.** `song.txt` contains "Life goes on as it never ends". What is the output?
```python
f1 = open("song.txt", "r")
s1 = f1.read(5)
s2 = f1.readline(4)
s3 = f1.read(3)
print(s1, s3, sep="#")
```
(A) `goes # on`  (B) `Life #goes # on`  (C) `Life # on`  (D) Error

✅ **Ans: (C) `Life # on`** — s1="Life ", s2="goes", s3=" on" (PYQ 2025)

**14.** `readlines()` returns:
(A) a single string  (B) the first line only  (C) the number of lines  (D) a list of all the lines

✅ **Ans: (D) a list of all the lines**

**15.** What is the advantage of `with open(...) as f:`?
(A) The file is closed automatically  (B) It reads faster  (C) No errors can happen  (D) It is binary-only

✅ **Ans: (A) The file is closed automatically**

**16.** `f.seek(0)`:
(A) moves the file pointer to the beginning  (B) moves it to the end  (C) closes the file  (D) reads one byte

✅ **Ans: (A) moves the file pointer to the beginning**

**17.** `f.tell()` returns:
(A) the file size  (B) the number of lines  (C) the current position of the file pointer  (D) the file name

✅ **Ans: (C) the current position of the file pointer**

**18.** Which module saves Python objects into binary files?
(A) pickle  (B) csv  (C) os  (D) math

✅ **Ans: (A) pickle**

**19.** `pickle.dump()` is used to:
(A) read an object from a file  (B) write an object to a binary file  (C) delete a file  (D) close a file

✅ **Ans: (B) write an object to a binary file** — `load()` reads

**20.** Which mode opens a binary file for reading?
(A) `'r'`  (B) `'wb'`  (C) `'ab'`  (D) `'rb'`

✅ **Ans: (D) `'rb'`**

---

## H. Modules & Libraries

**1.** Which module must be imported to use a double-ended queue?
(A) collections  (B) counter  (C) random  (D) numpy

✅ **Ans: (A) collections** — `from collections import deque` (PYQ 2025)

**2.** `import math; print(math.sqrt(16))`
(A) 4  (B) 4.0  (C) 16  (D) 2

✅ **Ans: (B) 4.0** — sqrt returns a float

**3.** `print(math.ceil(4.2))`
(A) 4  (B) 4.2  (C) 5  (D) 4.0

✅ **Ans: (C) 5**

**4.** `print(math.floor(-2.5))`
(A) -2  (B) -3  (C) -2.5  (D) 2

✅ **Ans: (B) -3** — Rounds toward −∞

**5.** `random.randint(1, 6)` returns:
(A) an integer from 1 to 6, both included  (B) an integer from 1 to 5  (C) a float  (D) a list

✅ **Ans: (A) an integer from 1 to 6, both included**

**6.** `random.random()` returns:
(A) 0 or 1  (B) a float in (0, 1]  (C) an integer from 1 to 10  (D) a float in [0.0, 1.0)

✅ **Ans: (D) a float in [0.0, 1.0)**

**7.** `statistics.mode([1,2,2,3])`
(A) 1  (B) 2  (C) 3  (D) 2.0

✅ **Ans: (B) 2**

**8.** `statistics.median([1,3,5,7])`
(A) 4.0  (B) 3  (C) 5  (D) 16

✅ **Ans: (A) 4.0** — (3 + 5) / 2

**9.** After `from math import pi`, you can use:
(A) `pi` directly  (B) only `math.pi`  (C) neither  (D) only `Math.PI`

✅ **Ans: (A) `pi` directly**

**10.** Which keyword gives a module an alias (`import pandas __ pd`)?
(A) `as`  (B) `alias`  (C) `rename`  (D) `to`

✅ **Ans: (A) `as`**

**11.** `dir(module)` returns:
(A) a list of the names defined in the module  (B) its documentation  (C) its version  (D) its file path

✅ **Ans: (A) a list of the names defined in the module**

**12.** `help()` shows:
(A) a list of variables  (B) the version  (C) documentation  (D) the source path

✅ **Ans: (C) documentation**

**13.** Which library is used for numerical arrays?
(A) NumPy  (B) Pandas  (C) Matplotlib  (D) Tkinter

✅ **Ans: (A) NumPy**

**14.** Which library is used for plotting graphs?
(A) NumPy  (B) Matplotlib  (C) pickle  (D) csv

✅ **Ans: (B) Matplotlib**

**15.** Which built-in library is used for GUIs?
(A) NumPy  (B) pandas  (C) math  (D) tkinter

✅ **Ans: (D) tkinter**

**16.** Which tool installs Python packages?
(A) pip  (B) npm  (C) apt  (D) gem

✅ **Ans: (A) pip**

**17.** `os.getcwd()` returns:
(A) the current working directory  (B) the user name  (C) the OS version  (D) the date

✅ **Ans: (A) the current working directory**

**18.** A module is:
(A) a .py file containing Python code  (B) a folder  (C) a class  (D) a variable

✅ **Ans: (A) a .py file containing Python code**

**19.** A package is:
(A) a single function  (B) a single variable  (C) a collection of modules in a folder  (D) a class

✅ **Ans: (C) a collection of modules in a folder**

**20.** `if __name__ == "__main__":` is true when the file is:
(A) imported  (B) run directly  (C) always  (D) never

✅ **Ans: (B) run directly**

---

## I. Stack & Queue in Python

**1.** A stack works on the principle of:
(A) LIFO  (B) FIFO  (C) random access  (D) priority

✅ **Ans: (A) LIFO**

**2.** A queue works on the principle of:
(A) LIFO  (B) FIFO  (C) random access  (D) none of these

✅ **Ans: (B) FIFO**

**3.** Using a list as a stack, how do you push an item?
(A) `append()`  (B) `insert(0, x)`  (C) `pop(0)`  (D) `extend()`

✅ **Ans: (A) `append()`**

**4.** Using a list as a stack, how do you pop the top item?
(A) `pop(0)`  (B) `remove()`  (C) `pop()`  (D) `clear()`

✅ **Ans: (C) `pop()`**

**5.** Using a list as a queue, how do you remove the front item?
(A) `pop(0)`  (B) `pop()`  (C) `remove()`  (D) `del L[-1]`

✅ **Ans: (A) `pop(0)`**

**6.** Pushing onto a full stack causes:
(A) overflow  (B) underflow  (C) nothing  (D) a sort

✅ **Ans: (A) overflow**

**7.** Popping from an empty stack causes:
(A) overflow  (B) nothing  (C) a sort  (D) underflow

✅ **Ans: (D) underflow**

**8.** Which queue allows insertion and deletion at both ends?
(A) circular queue  (B) linear queue  (C) deque  (D) priority queue

✅ **Ans: (C) deque** — (PYQ 2025)

**9.** Which deque method adds an item at the left end?
(A) `appendleft()`  (B) `addleft()`  (C) `pushleft()`  (D) `insertfirst()`

✅ **Ans: (A) `appendleft()`** — `popleft()` removes from the left

**10.** Which is the most efficient way to implement a queue in Python?
(A) `collections.deque` (O(1) at both ends)  (B) `list.pop(0)`  (C) a tuple  (D) a set

✅ **Ans: (A) `collections.deque` (O(1) at both ends)**

**11.** A stack is used in:
(A) function calls/recursion, undo, expression evaluation  (B) BFS  (C) printer queues  (D) round-robin scheduling

✅ **Ans: (A) function calls/recursion, undo, expression evaluation**

**12.** A queue is used in:
(A) DFS  (B) BFS and job scheduling  (C) recursion  (D) undo

✅ **Ans: (B) BFS and job scheduling**

**13.** What is the postfix form of `A + B * C`?
(A) `ABC*+`  (B) `AB+C*`  (C) `+A*BC`  (D) `AB*C+`

✅ **Ans: (A) `ABC*+`**

**14.** Evaluate the postfix expression `3 5 * 6 + 2 3 * -`.
(A) 21  (B) 9  (C) 15  (D) 27

✅ **Ans: (C) 15** — 3×5=15, 15+6=21, 2×3=6, 21−6=15

**15.** Starting with an empty stack: push 1, push 2, pop, push 3. What is on top?
(A) 1  (B) 2  (C) empty  (D) 3

✅ **Ans: (D) 3**

**16.** The peek (top) operation:
(A) returns the top element without removing it  (B) removes the top element  (C) empties the stack  (D) sorts the stack

✅ **Ans: (A) returns the top element without removing it**

**17.** When a Python list is used as a stack, the top element is:
(A) `L[0]`  (B) `L[-1]`  (C) `L[1]`  (D) the middle element

✅ **Ans: (B) `L[-1]`**

**18.** Converting infix to postfix uses a:
(A) stack  (B) queue  (C) tree  (D) set

✅ **Ans: (A) stack**

**19.** In a priority queue, elements are served:
(A) by priority  (B) strictly FIFO  (C) strictly LIFO  (D) randomly

✅ **Ans: (A) by priority**

**20.** `q = []; q.append(1); q.append(2); print(q.pop(0))`
(A) 2  (B) 1  (C) `[2]`  (D) an error

✅ **Ans: (B) 1** — FIFO

---

## J. Pandas & NumPy Basics

**1.** Which is a 2-D labelled data structure with a row index and column index?
(A) DataFrame  (B) Series  (C) list  (D) tuple

✅ **Ans: (A) DataFrame** — (PYQ 2025)

**2.** Which is a 1-D labelled array?
(A) DataFrame  (B) Series  (C) Panel  (D) dict

✅ **Ans: (B) Series**

**3.** Which function returns the first n rows of a DataFrame?
(A) `head(n)`  (B) `top(n)`  (C) `first(n)`  (D) `get(n)`

✅ **Ans: (A) `head(n)`** — (PYQ 2025)

**4.** Which function returns the last n rows?
(A) `last(n)`  (B) `bottom(n)`  (C) `tail(n)`  (D) `end(n)`

✅ **Ans: (C) `tail(n)`**

**5.** By default, `head()` returns how many rows?
(A) 5  (B) 10  (C) 3  (D) all of them

✅ **Ans: (A) 5**

**6.** What is the standard alias for pandas?
(A) `pd`  (B) `pn`  (C) `pa`  (D) `pds`

✅ **Ans: (A) `pd`**

**7.** `df.shape` returns:
(A) a (rows, columns) tuple  (B) the number of rows only  (C) the column names  (D) the data types

✅ **Ans: (A) a (rows, columns) tuple**

**8.** `df.columns` gives:
(A) the rows  (B) the values  (C) the index  (D) the column labels

✅ **Ans: (D) the column labels**

**9.** Which function reads a CSV file into a DataFrame?
(A) `pd.read_csv()`  (B) `pd.open_csv()`  (C) `pd.load()`  (D) `pd.csv()`

✅ **Ans: (A) `pd.read_csv()`**

**10.** Which method writes a DataFrame to a CSV file?
(A) `df.write_csv()`  (B) `df.to_csv()`  (C) `pd.save()`  (D) `df.export()`

✅ **Ans: (B) `df.to_csv()`**

**11.** How do you select the column 'Name'?
(A) `df['Name']`  (B) `df(Name)`  (C) `df{Name}`  (D) `df<Name>`

✅ **Ans: (A) `df['Name']`** — `df.Name` also works

**12.** `iloc` selects data by:
(A) label  (B) column name only  (C) integer position  (D) boolean only

✅ **Ans: (C) integer position** — `loc` selects by label

**13.** In a Series, the size is:
(A) immutable (the values can still change)  (B) mutable  (C) undefined  (D) always 1

✅ **Ans: (A) immutable (the values can still change)**

**14.** In a DataFrame, the size and values are:
(A) mutable  (B) immutable  (C) read-only  (D) fixed at 5

✅ **Ans: (A) mutable**

**15.** `df.describe()` gives:
(A) summary statistics  (B) the structure only  (C) the column names  (D) the first row

✅ **Ans: (A) summary statistics**

**16.** All elements of a NumPy array must be:
(A) of different types  (B) of the same type  (C) strings  (D) none of these

✅ **Ans: (B) of the same type**

**17.** `print(np.arange(0, 10, 2))`
(A) `[0 2 4 6 8]`  (B) `[0 2 4 6 8 10]`  (C) `[2 4 6 8]`  (D) `[0 10 2]`

✅ **Ans: (A) `[0 2 4 6 8]`** — The stop value is excluded

**18.** `np.zeros(3)` creates:
(A) `[0. 0. 0.]` (floats)  (B) `[0, 0, 0]` as a list  (C) `[3]`  (D) an error

✅ **Ans: (A) `[0. 0. 0.]` (floats)**

**19.** How are missing values shown in pandas?
(A) NULL  (B) 0  (C) ''  (D) NaN

✅ **Ans: (D) NaN**

**20.** `df.drop('col', axis=1)` drops:
(A) a row  (B) all rows  (C) a column  (D) the index

✅ **Ans: (C) a column** — axis=0 is rows

---

### Score tracker

| Topic | Attempt 1 | Attempt 2 |
|---|---|---|
| A. Basics & data types | /20 | /20 |
| B. Operators | /20 | /20 |
| C. Strings | /20 | /20 |
| D. Lists & tuples | /20 | /20 |
| E. Dictionaries & sets | /20 | /20 |
| F. Control flow & functions | /20 | /20 |
| G. Exceptions & files | /20 | /20 |
| H. Modules & libraries | /20 | /20 |
| I. Stack & queue | /20 | /20 |
| J. Pandas & NumPy | /20 | /20 |
| **Total** | **/200** | **/200** |
