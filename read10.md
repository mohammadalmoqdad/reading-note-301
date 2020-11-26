# call stack:
* it is a mechanism for an interpreter to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function.
* When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
* Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
* When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
* If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.
* ***LIFO:*** When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.
* When the code is run, we get an error. A stack is printed showing how the functions are stack on top each other.
* **stack frame** is a memory location in the stack. The memory is cleared when the function returns as it is pop out of the stack.
* ***Temporarily store:*** When a function is invoked (called), the function, its parameters, and variables are pushed into the call stack to form a stack frame.


# Types of error messages:
* Reference errors: when what we excuting is not inishilized or assigned with a value, or BECAUSE declaring variable after assigning a value to it.
* Syntax errors: this occurs when you have something that cannot be parsed in terms of syntax.
* Range errors: when trying to make an operation on something not in the range of operations.
* Type errors: this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.
* 