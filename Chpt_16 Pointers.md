# Pointers

A pointer is simply an **address** pointing somewhere inside the computer’s memory, with a type specifier so you
get the right size of data with it. C knows where pointers are pointing, knows the data type they point at, the size of those types, and how to get the data for you. 

The purpose of a pointer is to let you manually index into blocks or memory when an array won’t do it right.
A pointer gives you raw, direct access to a block of memory so you can work with it.


## Four Basic usages:

>1. Ask the OS for a chunk of memory and use a pointer to work with it. This includes strings and something
>you haven’t seen yet, structs.
>2. Passing large blocks of memory (like large structs) to functions with a pointer so you don’t have to pass the
>whole thing to them.
>3. Taking the address of a function so you can use it as a dynamic callback.
>4. Complex scanning of chunks of memory such as converting bytes off a network socket into data structures
>or parsing files.


## The Pointer Lexicon

>**type** ***ptr** "a pointer of type named ptr"

>***ptr** "the value of whatever ptr is pointed at"

>***(ptr + i)** "the value of (whatever ptr is pointed at plus i)"

>**&thing** "the address of thing"

>**type** ***ptr = &thing** "a pointer of type named ptr set to the address of thing"

>**ptr++** "increment where ptr points"



