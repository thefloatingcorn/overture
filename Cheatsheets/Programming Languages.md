# Programming

<!-- ## Default -->

## Comparison
Languages: Python, C, C++, Java

Variable naming: letters, digits, underscore

Scope: block based

Loop: while, for; break, continue

Operator: !=, //, %, ||, &&, &, \, ^, <<, >>

Operator Precedence

Ternary conditional operator

Multiple Inheritance: Python, C++

### Comment
* Python: single line (#), multiple lines (''' or """)
* Java: //

### Formatting Strings
* Python:
  * "{} {}".format(x, y)
  * "{1:d} {0:d}".format(y, x)
* C: printf(); %d, %c, %s, %f

### String
* Python: 'xxx', "xxx"

### Length
* Python: len(A)
* Java: A.length; aString.length()
* C++: A.size()

### Print
* Java: System.out.println(var + " ");

### Array
* Java: dataType[] arrayRefVar; dataType arrayRefVar[];
  * dataType[] arrayRefVar = new dataType[arraySize];
  * dataType[] arrayRefVar = {value0, value1, ..., valuek};
* C/C++: dataType arrayRefVar[];

### Float Calculation
* Python: 3 / 2 (=1.5); 3 // 2 (=1); 0.1+0.1-0.2 (!=0)
* Java: 3.0 / 2 (=1.5); 3 / 2 (=1)

### Type
* Python: int, float, str, bool, NoneType
* Java: int, double, long, Boolean, String, Character

### Operator
Python:
Java: &&

### Infinite
Python: float("inf"), float("-inf")
C++: INT_MAX, INT_MIN
Java: Integer.MAX_VALUE, Integer.MIN_VALUE

### Initialise
* Python: thisInstance = TheClass()

### Inheritance1
* Python: class TheSubClass(TheSuperClass): ...
* Java: public class TheSubClass extends TheSuperClass {...

### Inheritance2
* Python: super().theMethod()
* Java: super.theMethod()
* C++: TheSuperClass::theMethod()


## Python

### Default

myList = [0] * n

decorator: @; wrapper (e.g. timer)

generator: yield

Arguments list: \*args

Keyword arguments: \**args

list: extend()

set: add(), update()

timeit

{}.fromkeys()

if 1 <= x <= 2:

### Tips

* range() only support integer step: e.g. range(0,1,0.1) is invalid.

### Standard modules:
sys, os, random, datetime, calendar, shutil, urllib, json, html, xml, platform, decimal

### Type (class):
* Base: int, float, str, bool, NoneType
* Sequence: tuple, list, dict, set

### Exception handling
Keyword: try, except, else, finally; raise
Exception: ValueError, TypeError

### Functions
* Basic: id, type, isinstance, ord, chr
* Container functions: any, all,

### Key words
* Basic: def, del, with ... as ..., elif, yield
* Boolean Operators: not, in, is, and, or

### Naming
* Protect(self and subclass): \_xxx
* Private(self only): \_\_xxx
* Differ from keyword: xxx_
* Special: xxx__

> if __name__ == '__main__': main()


## C

No string type

short int: 2 or 4 bytes (default signed)

float: 4 bytes

long = 2 * short, double = 2 * float, long double = 2 * double

\#define VALUE 10

static, extern

## C++

inline functions: substitution performed by compiler.

const:
read from right to left;
the first const can be on either side.

nullptr is pointer-type; NULL is value-type int.

Const check compile time

free() for malloc();
delete for new.

typename / class can be replaced in template<>

Abstract class: if including pure virtual function.

* objectName/reference.memberName
* pointer->memberName
* className::memberName

virtual, override, final

private by default

overloaded as streaming operators ( << then means stream out, >> stream in


## Java
List:ArrayList, Set:HashSet, Map:HashMap


int[] A = new int[N];
A[A.length-1]

Math.max()
s.charAt()
Set<Character> set = new HashSet<>();
Deque<Integer> monoq = new LinkedList();


## C\#

type: int, float, char, string, bool

Console.WriteLine("Hello World!");

Class members are private by default.
