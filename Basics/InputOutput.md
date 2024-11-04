First we need to include `iostream`, so we have the functionality to input and output info in C++.

We can also include `using namespace std` in our code, to save us from typing `std::` to use anything. -> This will basically means that for everything in our code that is a function, and needs components like variables, functions, and things to work properly, it will request inside the `namespace` we are using. In this case -> `std` (standard)

#### Functions
`cout` -> Output
`cin` -> Input
`endl` -> Endline 

In c++ we need to redirect info through and from output and input. 
What does that mean? Let's say we want to put "Hello world" in our terminal, if we want to do that, we need to send that information to the `cout` stream, so it posts it on the terminal.

We would do that by: `std::cout << "Hello world" << std::endl;` -> (<< and >> is basically a way to tell if we're sending to or from something)

We can also input info in some variables by using the same principle. 
`std::cin >> value` -> Would send the inputted value to the variable value.
