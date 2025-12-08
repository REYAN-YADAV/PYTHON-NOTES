# Python Complete Notebook 

## 1. What is Language?
> **Definition:**  
A *language* is a systematic method of communication used to exchange ideas, instructions, or information.

### Types of Languages
| Type | Description | Examples |
|------|-------------|----------|
| **Natural Language** | Used by humans for communication | English, Hindi |
| **Formal Language** | Used by computers; follows strict rules | Python, C, Java |

---

## 2. What is a Program?
> A **program** is a set of instructions written by a programmer to perform a specific task.

### Characteristics
- Follows a sequence  
- Can be executed by a computer  
- Written using any programming language  

---

## 3. Types of Programming Languages
Programming languages are broadly divided into:

| Category | Description | Examples |
|----------|-------------|----------|
| **Low-Level Languages** | Close to hardware; fast but difficult | Machine Language, Assembly |
| **High-Level Languages** | Easy to understand; closer to English | Python, Java, C++ |
| **Scripting Languages** | Execute scripts; used for automation | Python, JavaScript |
| **Domain-Specific Languages** | Built for specific use cases | SQL, HTML |

---

## 4. Low Level Languages

### a) Machine Language
> **Definition:** Machine language is the lowest-level programming language consisting of binary digits (0s and 1s).

### Example
```
0001 1001 1100
```

### Advantages
- Fastest execution  
- No translator needed  

### Disadvantages
- Hard to read  
- Error-prone  
- Machine-dependent  

---

## 5. Assembly Language
> A symbolic low-level language using mnemonics instead of binary.

### Example
```
MOV A, B
ADD A, 10
```

### Advantages
- Easier than machine language  
- Faster execution  

### Disadvantages
- Still hardware dependent  
- Harder than high-level languages  

### What is an Assembler?
An **assembler** converts assembly code → machine code.

---

## 6. Translators: Interpreter & Compiler
Computers cannot directly understand high-level languages.  
So we use **translators**.

### Types of Translators
| Translator | Works On | Converts To | Style |
|------------|-----------|-------------|-------|
| **Interpreter** | Line-by-line | Machine Code | Finds errors immediately |
| **Compiler** | Whole program | Machine Code | Faster execution |

---

## 7. Tokens
> The smallest unit in a program.
> ex-> a = 10 here, a is variable and also a token
>                   = is assignment operator and also a token
>                   10 is constant also a token

### Types of Tokens
- Keywords  
- Identifiers  
- Operators  
- Literals  
- Punctuators  

---

## 8. Scripting Languages
> Scripting languages are used to automate tasks and execute scripts.

### What is a Script?
A script is a small program written to automate a process.

### Examples
- Python  
- JavaScript  
- Shell Script  

---

## 9. Programming Paradigms
Different styles of writing programs.

| Paradigm | Full Form | Description |
|----------|------------|-------------|
| **POP** | Procedure Oriented Programming | Program divided into functions |
| **OOP** | Object Oriented Programming | Uses objects & classes |
| **SOP** | Structured Oriented Programming | Uses blocks, loops, conditions |
| **MOP** | Modular Oriented Programming | Divides program into modules |

---

## 10. Introduction to Python
Python is a high-level, interpreted, object-oriented language.

### Features
- Easy to learn  
- Interpreted  
- Portable  
- Open-source  
- Large standard library  

### Purpose-Based Languages
| Type | Use |
|------|-----|
| System Language | Hardware control |
| Application Language | Apps, software |
| Scripting Language | Automation |

---

## 11. Real-Time Applications of Python

### 1. Web Development
Frameworks:
- Django  
- Flask  

### 2. Desktop Applications
- Tkinter  
- PyQT  

### 3. Data Science
- NumPy  
- Pandas  
- Matplotlib  

### 4. Artificial Intelligence / ML
- TensorFlow  
- PyTorch  

### 5. Automation
- Selenium  
- Scripts  

### 6. Cybersecurity
- Pen-testing  
- Packet analysis  

### 7. Blockchain
- Crypto apps  
- Smart contracts  

---

## 12. CAD, CAM, ERP

### CAD
Computer-Aided Design  
Used in:
- Engineering  
- Architecture  
- 3D modeling  

### CAM
Computer-Aided Manufacturing  
Used in:
- CNC machining  
- Manufacturing automation  

### ERP
Enterprise Resource Planning  
Used in:
- Inventory  
- Finance  
- Business automation  

---

# GETTING STARTED WITH PYTHON.
---
## History of Python
- python programming language conceived in the year 1980.
- python programming language was started its implementation (Bring into action)  in the year 1989.
- Python programming language was officially released to the industry in the year 1991 feb.
- Python programming language Developed by "GUIDO VAN ROSSUM"(Father of python).
- Python programming language developed at Centrum Winkunde Informatica (CWI) in Netherlands.
- Rossum has studied ABC programming language for development of python programming.Hence python programming language is one of the successor ABC language.
- First python programming language developed and executed on Ameba OS.
- Python programming language maintained and managed by Non-Commercial organization "PYTHON SOFTWARE FOUNDATION"(PSF).
---
## Versions Of Python
- Python programming contain 3 Types of versions.They are
  1. **Python 1.X** -> Here 1 is called major and x is called minor version and it represents 0,1,2,3,4,5,6 etc..
    As on today python 1.x is outdated.
    -Python 2.x does not contain Backward compatibility with python 1.x.
  2. **python 2.x** -> here 2 is called major versions and x is minor versions it represents 0,1,2,3,4,5,6,7 As of today python 2.x is outdated 
  -Python 3.x does not contain Backward compatibility with python 2.x.
  3. **python 3.x** -> here 3 is called major versions and x is minor versions it represents 0,1,2,3,4,5,6,7,8,9,10,11,12,13,14 - upcoming 
   - python 3.13.6 , Here 3->represent major version , 13->minor version, 6 -> represent alpha beta version
   - **compatibility** -> That can work well together , get along well together
   - **version** -> A thing which has the same basic contents as something else but which is represent in different way.
  ---
  ## Features Of Python Programming Language
  - Features of programming language are nothing but services or facilities provided by language developer and they are available in programming language and they used by language programmers for developing real time projects and applications.
  - Python programming have 11 features.They are
  - 
  1. ### Simple
   - Python programming language is one of the simple programming language because of 3 important technical factors.
   - *Factor 1*
   - python programming language provides rich set of modules, so that python programmers can learn multiple modules and They can re-use the pre-defined code present in modules without writing their own code.
   - **Definition of Modules** 
            A module is a collection of data members, functions and class Names.
        *ex* -> Calender, math, cmath, os, random etc..
    -
    - *Factor 2*
    -python program provides In-built Facility called "Garbage Collector". So that Garbage Collector collects un used memory space and improves the performance of python Based Applications.
    -**Definition of Garbage Collectors**
        A Garbage collectors is one of the python Background program which is available in python software and running behind of python Regular program and role is to collect un used memory space and improves the performance of python based applications.
        - Hence Garbage collector take care about automatic memory management.
    - *Factor 3*
    - python programming provides user friendly syntax.So that python programmers can develop Error-Free programs in limited span of time.
    - *Ex ->* ```import calendar as c
                 print(c.month (2024,5))
               ```
2. ### Platform Independent
   - A platform is nothing but type of OS being used (OS acts as Resource Allocation and De-location manager). In   IT
   we have two types of programming language.They are 
        1. *Platform Dependent language*
          - In platform dependent language data types differs from one OS to another OS.
        *EX->* c, c++ etc..
        2. *platform Independent Language*
        - In platform Independent language data types memory space remain same in all type OSes.
   - In effective platform Independent language all types of values will store in the form of objects. and they can store un-limited amount of data.
   - Hence java objects contains size restricted where python objects contains unlimited size and unlimited values can store.
   - **Note ->** In python all values are stored in the form of objects.
     - *ex->* java,python
3. ### Dynamically Typed
   - In IT we have two  types of programming language they are
   - 1. **Static type programming language**
      - In static typed programming language it is mandatory to use data types along with the variables name(Variable Declaration) otherwise it show compiler Time error.
      - *ex->* c, c++,java,c# etc..
      -  ``` int a,b,c //variable declaration
                   a = 10;
                   b = 20;
                   c = a+b;
                           ```
     2. **Dynamically Typed language**
    - In Dynamically Typed programming language programmers will not assign any data types, Internally language execution environment will assign the data type automatically or implicitly based on the type of value programers uses/assign.
    - *Ex->* python
       ``` a=10
           b=20
           c = a*b
           print(a,type(a))
           print(b,type(b))
           print(c,type(c))
           ```
4. ### Interpreted
   -When we develop any python program we must give som file name with an extension .py(filename.py)
   when we execute that file two process taken place internally
    -a) **compilation process**
      - IN compilation process, The python source code submitted to to python compiler and it reads the source code(line by line),checks for errors by verifying syntaxes and if no errors found then python compiler converts into intermediate code called byte code with an extension .pyc(filename.pyc).if errors found in source code then we get error display on console.
    - b) **execution process**
     - In execution process, The PVM reads the python intermediate code (byte code) line by line and converts into machine understandable code (executable or binary code) and it read by OS and processor and finally gives result.
 - Hence in python program execution the compilation and execution process is taking line by line conversion and it is one of the interpretation based programming language.
 - ### definition of PVM (python virtual machine)
  - PVM is one program in python software and whose role is to read line by line byte code and converts into machine understandable code (executable or binary code). extension - .exe
Q.) * what is byte code ?*
 - compiled code of python source code is called byte code .
 - it is intermediate code of python execution environment .
 - its extension is .pyc
 - it is platform independent code
 - it is understandable by PVM.       
          
5. ### Freeware and Open Source
  - *freeware ->* if any software download freely from official source (www.python.org)/ website then that software is freeware. ex- python
  - *open source ->* After downloading the software from official source and vendor do some customization process then that type of software is called open source.
  - The customized version of original software are called "Distributions"
  - In case python, The standard name of python is called 'cpython'
  - many software companies come forward and customized CPYTHON for developing their own in-house Tools these customized versions are called "python Distributors" 
  - Some of "Python Distributions are 
  - 1. *jpython or jython ->* it is used for running java based software
  - 2. *Iron python or Ipython ->* it is used for c#.net based applications
  - 3. *micro python ->* it is used to develop and run micro controller application
  - 4. *Ruby python ->* it is used ofr Ruby based application
  - 4. *Anaconda python ->* it  is used to run Hadoop/ Big data application. etc...
6. ### High Level
   - In this context we have two type of language 
   - 1. **Low level language**
     - In low programming language data is always stored in the form low level values such as binary data, octal data, and hexa decimal data. These Number system are not directly understandable by end users.
    *ex->* a = ob10101 -> Binary
          b = oxBEe -> Hexa decimal
   - 2. **High level language**
   - In these language, Internally ,Even the programmer specifies the data in the form of low level format such as binary data , octal, hexa decimal data, automatically python programming language execution environment converts into high level data which is understandable by end-users.
   - Hence python is one of the High level programming language.
   - *ex->* ``` a = 0b101010
                print(a)
                b = 0bBEe
                print(b) ```
7. ### Robust(Strong)
   - python programming language is one of th robust programming language because it provides a prograsmming model called "Exceptional Handling"
   - **Exception**
   - Every Run time Error is called exception .
   - When enf-user put wrong or invalid input then we get runtime error or exception
   - All runtime error or exceptional by default generates Technical error message understandably programmers but not by end-users. industry always recommends to convert Technical error message into user-friendly error message by using exception handling.
- **Exception Handling**
- The process of converting technical error message into user-friendly error messages is called Exception Handling.
- Every real Time project of all language uses Exception Handling for building Robust Application.
  ---
## Type of errors in programming language
1. **compile Time errors ->** when syntaxes are wrong
2. **Logical Errors->** Runtime/Execution time because programmers not following correct logic / wrong representation of formulas or logics - wrong output
3. **Runtime errors->** Runtime/Execution Time technical error or user friendly error.
---
8. ### Extensible
  - python programming its modules service to other language
  - programmers for easy to use by writing less code with more meaning since python provides its service to other language and Hence python is one of the Extensible Language.
9. ### Embedded
  - python programming will use other language services/libraries also in other words , We call other language code inside of python program and Hence python programming lang is Embedded programming language.
10. ### Supports Third party Api.
  - most of the time python programming supports Third party Api such as numpy,padas, etc.. are providing Easiness to python programmer in case of complex math calculation (numpy) , business analytics (pandas). etc..
  

  

   
 
             
  