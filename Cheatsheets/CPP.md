# C Plus Plus
*Including some notes from the C++ Primer book.*

## Default
* C++ is a statically typed language, which means that types are checked at compile time. 
* It can be easier to understand complicated pointer or reference declarations if you read them from right to left. 
* Expressions that mix signed and unsigned values can yield surprising results when the signed value is negative. It is essential to remember that signed values are automatically converted to unsigned. 
* Integer literals that begin with 0 (zero) are interpreted as octal. Those that begin with either 0x or 0X are interpreted as hexadecimal. 

## Types
* https://en.cppreference.com/w/cpp/language/types
  * short 16, int 32, long 32, long long 64
  * float 32, double 64

* Use double for floating-point computations
  * float usually does not have enough precision, and the cost of double-precision calculations versus single-precision is negligible. 
  * The precision offered by long double usually is unnecessary and often entails considerable run-time cost. 

* Use int for integer arithmetic. short is usually too small and, in practice,
  * long often has the same size as int. 
  * If your data values are larger than the minimum guaranteed size of an int, then use long long.

## Keywords
* Extern: Variables must be defined exactly once but can be declared many times. To share a const object among multiple files, you must define the variable as extern. 
* [Explicit](https://en.cppreference.com/w/cpp/language/explicit): https://stackoverflow.com/questions/121162/what-does-the-explicit-keyword-mean
* volatile: [prevents the compiler from optimizing code](https://stackoverflow.com/questions/4437527/why-do-we-use-volatile-keyword)
