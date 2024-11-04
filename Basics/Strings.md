This one differs from C, as it basically introduces string by being an element on itself, instead of just an array of characters it is an object.

To start manipulating strings.
`#include <string>`

Included using the `std::string` to reference the standard library namespace.

To declare a string you need first to indicate it to the code, **"it is a string"**, and to do so: `std::string variable = "my string here hehehe";`

To put an info inside a variable we can use cin.
- `our_string << std::cin;` -> This will get everything before an space
- `std::getline(std::cin, our_string);` -> This will get everything before the endline marker
