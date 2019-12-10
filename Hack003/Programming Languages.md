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

### Formatting Strings
* Python:
  * "{} {}".format(x, y)
  * "{1:d} {0:d}".format(y, x)
* C: printf(); %d, %c, %s, %f

### String
* Python: 'xxx', "xxx"

### Float Calculation
* Python: 3 / 2 (=1.5); 0.1+0.1-0.2 (!=0)

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

decorator: @; wrapper (e.g. timer)

generator: yield

Arguments list: \*args

Keyword arguments: \**args


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

short int: 2 or 4 bytes (default signed)

float: 4 bytes

long = 2 * short, double = 2 * float, long double = 2 * double

\#define VALUE 10

static, extern
