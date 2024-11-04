
### Conditionals 

Same thing as C

`if (condition) {} else if (other_condition) {} else {}`

### Loops

#### For loops
`for (variable = value, variable_condition, what_to_do_to_variable) {}`
Also, if you have already declared an variable, you can instead use it for reference in a different way.

```
int i = 10;
for (; i > 0; i--) {
	std::cout << i << std::endl;
}
```

Or, also, you could instead

```
int i = 10;
for (; i > 0; ) {
	std:: cout << i << std::endl;
	i--;
}
```

This would be kind of useful, but i don't see many using it in cp, so i don't know if i will use it too.

Also, in C++ 11 and later, we can iterate over an array, just like most modern languages.
`for (int n : arr) {}`

BUT, as in this way, we could modify the values, so it's best to use const for safety (if you aren't talking about cp, but i think in cp this isn't the main focus anyway)

Also, this is way over complicated, it isn't really a no-brainer like most languages, and there are some requirements, we need the full object, not the pointer, the size and to interact with it fully. That makes it really hard to use it on functions for example (at least with the default array), but it works just like normal when you use objects (on functions, if you use it on the main it is really a no-brainer). 

### While loops
Pretty standard, just like C

`while (condition) { }`