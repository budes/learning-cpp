- **Boolean** - `boolean` - either `true` or `false`
- **Characters** - alphabets and all the symbols. Defined using `char`.
- **Integers** - whole numbers which can be both positive and negative. Defined using `int` (4 bytes) or `short int` (2 bytes) or `long int` (8 bytes) based on the size of the numbers used.
- **Floating point numbers** - real numbers (numbers with fractions). Defined using `float` and `double`.
- **Valueless** using the `void` keyword
- **Wide character** using the `wchar_t` keyword

---
### Modifiers
- `signed` or `unsigned` -> Allows for more numbers represented without considering any negative numbers
- `long` or `short` -> Allows for more optimizations in order to represent more or less numbers
### Typedef
New names to already existing types
`typedef char letters` for example
### Enumeration
`enum enum_name {list_of_possibilities} a_var, b_var;`
What this basically does is if we have `{a, b, c}` in the variable, if the variable receives those values, it will be substituted for the index.

So, let's say we have
```
enum vocals {a, e, i, o, u} letter;
letter = e;
```
letter will, instead, receive the value 1;


