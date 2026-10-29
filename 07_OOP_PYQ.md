# Bihar STET Paper 2 (Computer Science): Object Oriented Programming PYQ Bank

**Papers covered:** the same 8 papers as the earlier chapters.

| Year | Paper | OOP questions found |
|---|---|---|
| 2019 | Second sitting | 3 |
| 2020 | Re-exam | 3 |
| 2023 | 12 Sep, Shift 1 | 7 |
| 2024 | 11 Jun (memory-based) | 2 |
| 2025 | 3 Nov Shift 1 | 8 |
| 2025 | 3 Nov Shift 2 | 4 |
| 2025 | 4 Nov Shift 2 | 4 |
| 2025 | 7 Nov Shift 1 | 8 |
| **Total** | | **≈39** |

> **Expect 4–8 OOP questions per shift.** They're all **one-line theory**: the definition of inheritance, overloading vs overriding, constructor vs destructor, abstract class vs interface, and keywords like `new`, `super`, `abstract` and `final`/`sealed`. There's no code. The language is general (Java/C#/C++ terms).
> **Several questions repeat word-for-word:** purpose of inheritance (2023 and 2025), information hiding (2023 and 2025), `new` (2023 and 2025), and the definition of overloading (3 times).

**Notes on answers**
- The questions are paraphrased.
- The 2023 answers come from the official key.
- For 2025, the answers were worked out from the options.
- For 2019–2020, these are the standard answers. The candidates' pen marks were often wrong.

---

## 1. Topic frequency

| Rank | Topic | Times asked | Years |
|---|---|---|---|
| 1 | **Inheritance** (purpose ×2, new class from existing, mechanism, multiple inheritance, Animal → Cat, `super`, `final`/`sealed`) | 9 | 2020, 2023, 2025 ×3 |
| 2 | **Polymorphism, overloading & overriding** (overloading ×3, overriding, polymorphism, method signature, polymorphism = OOP feature) | 8 | 2019, 2024, 2025 ×4 |
| 3 | **Classes, objects, constructors & destructors** (class = blueprint, object = instance, `new` ×2, object reference, constructor, destructor, ADT = class) | 9 | 2019, 2020, 2023, 2025 ×3 |
| 4 | **Abstract classes & interfaces** (abstract class, abstract method ×2, `abstract` keyword, interface purpose, abstract class vs interface) | 6 | 2023, 2025 ×3 |
| 5 | **Encapsulation, abstraction & information hiding** | 5 | 2019, 2020, 2023, 2025 ×2 |
| 6 | **Exceptions & paradigms** (exception definition, advantage, procedural programming) | 3 | 2025 ×3 |

---

## 2. Questions by topic (with answers)

### A. Inheritance
| # | Asked (paraphrased) | Answer | Year |
|---|---|---|---|
| 1 | Main purpose of inheritance | **Establishing a parent–child relationship between classes** | 2023, 2025 (3 Nov S1) |
| 2 | Term for creating a new class from an existing one | **Inheriting** | 2025 (7 Nov) |
| 3 | Mechanism by which a class gets the properties and behaviour of another | **Inheritance** | 2025 (7 Nov) |
| 4 | A class inheriting from several classes | **Multiple inheritance** | 2025 (7 Nov) |
| 5 | Which pair shows inheritance? (Animal → Cat, variable → constant, lock → key, data → program) | **Animal → Cat** | 2020 |
| 6 | Purpose of `super` | **It refers to the superclass (parent)** | 2023 |
| 7 | Keyword that stops a class from being inherited (sealed, final, private, static) | **final** (Java) **/ sealed** (C#). *Both are correct, so the question is ambiguous.* If the question names a language, answer for that language (Java → final, C# → sealed). | 2025 (3 Nov S2) |

### B. Polymorphism, overloading & overriding
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Same method name, different parameters | **Overloading** | 2024, 2025 (3 Nov S1, 3 Nov S2) |
| 2 | A class giving different implementations of a method depending on its input parameters | **Overloading** | 2025 (3 Nov S1) |
| 3 | A subclass gives its own implementation of a method already in the superclass | **Overriding** | 2025 (7 Nov) |
| 4 | Different classes treated as objects of the same parent class | **Polymorphism** | 2025 (4 Nov) |
| 5 | Method signature means | **The method name together with its parameter types** | 2025 (3 Nov S1) |
| 6 | Polymorphism is a feature of | **Object-oriented programming** | 2019 |

### C. Classes, objects, constructors & destructors
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Best definition of a class | **A blueprint for creating objects** | 2023 |
| 2 | Objects are | **Instances of classes** | 2019 |
| 3 | Keyword that creates an instance | **new** | 2023, 2025 (4 Nov) |
| 4 | Variable that refers to an instance of a class | **Object** | 2025 (4 Nov) |
| 5 | Purpose of a constructor | **Initialising the object's properties** | 2025 (3 Nov S1) |
| 6 | Purpose of a destructor | **Freeing resources when an object is destroyed** | 2025 (7 Nov) |
| 7 | Which is an abstract data type? (class, double, int, string) | **class** | 2020 |

### D. Abstract classes & interfaces
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | An abstract class is | **A class that cannot be instantiated** | 2023 |
| 2 | Abstract methods are | **Methods with no body, declared in an abstract class** | 2023 |
| 3 | A method with no implementation in the base class that derived classes must override | **Abstract method** | 2025 (3 Nov S2) |
| 4 | Keyword for declaring an abstract method | **abstract** | 2025 (4 Nov) |
| 5 | Main purpose of an interface | **Declaring methods that implementing classes must provide** | 2025 (7 Nov) |
| 6 | Advantage of an abstract class over an interface | **It can provide default (implemented) methods** | 2025 (3 Nov S1) |

### E. Encapsulation, abstraction & information hiding
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Principle that shows only essential information to the outside world | **Information hiding** (the official answer; abstraction is a close second) | 2023, 2025 (3 Nov S1) |
| 2 | What encapsulation is | **Bundling data with the methods that operate on it** | 2024, 2025 (7 Nov) |
| 3 | What a class encapsulates | **Functions and data** | 2020 |
| 4 | Abstraction means (summarisation, elimination, hiding, casting) | **Hiding** (of implementation details) | 2019 |

### F. Exceptions & paradigms
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | A condition that disrupts the normal flow of a program | **Exception** | 2025 (3 Nov S1) |
| 2 | Main advantage of exception handling | **Handles unexpected errors and lets the program end gracefully** | 2025 (7 Nov) |
| 3 | Paradigm that breaks a program into procedures/functions | **Procedural programming** | 2025 (3 Nov S2) |

---

## 3. Must-revise checklist

1. **Four pillars:** encapsulation, abstraction, inheritance, polymorphism. Know the definition of each **word-for-word**.
2. **Class vs object:** a class is a blueprint, an object is an instance; data members vs member functions; `new`; object reference.
3. **Constructors:** same name as the class, no return type, called automatically; default, parameterised, copy and overloaded constructors; Python `__init__`.
4. **Destructors:** `~ClassName` in C++, one per class, no arguments, free resources; Python `__del__`; Java uses garbage collection.
5. **Access specifiers:** private, protected, public (C++ class default = private); getters/setters; Python `_x` / `__x`.
6. **Inheritance:**
   - Types: single, multiple, multilevel, hierarchical, hybrid.
   - "is-a" vs composition "has-a".
   - The diamond problem is solved with virtual base classes.
   - Keywords: `extends`/`implements`, `super`, `final`/`sealed`.
7. **Polymorphism:**
   - Compile-time: overloading (same name, different parameters; the return type alone isn't enough).
   - Run-time: overriding, virtual functions.
   - Operator overloading, method signature, static vs dynamic binding.
8. **Abstract class vs interface:**
   - An abstract class can't be instantiated, can have constructors, and can mix concrete and abstract methods.
   - An interface declares a contract; a class can implement many; Java 8+ allows default methods; a pure virtual function is written `= 0`.
9. **Static, `this`/`self`, `super`, friend functions, scope resolution `::`.**
10. **Exceptions:** try/catch/throw/throws/finally (Java/C++), try/except/else/finally/raise (Python), checked vs unchecked.

Practice set: `07b_OOP_Practice_MCQs.md`
