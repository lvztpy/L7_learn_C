//Go through chapter1-5

# Nov-16th Chapter 1-5

1. So far , I installed a ubuntu 18.04 lts  virtual machine onto Vmware 15.

2. Installed *Vim*, a editor; *Okular*, a reader, which I use as a PDF file reader, because I got lots of PDF books. And I need a good tool to get along with. On windows I use sumatru

3. To start learn C language. I searched online for some resource.

	3.1 The  C programming language
	3.2 Learn C the hard way
	3.3 A programmer’s perspective on computer system

And I believe these three books are classical, if I go through with them , I will be a good programmer finally.

Here I got the first 4 chapters:
	I’ve made some set-ups or we can call them tools, 1)make (Makefile), 2)Valgrind, they helps a lot. Automate things.


From chapter 5-7
>
We get an idea on, what a typical program structure is , what is the variable (types), how to declare and assign value to them,  by using simple program.
>
C is all about the size and location of pieces of memory and what you do with them.
>
Sizeof() is a function to find how big something is.
To C, a "character" is just an integer. It’s a really small integer, but that’s all it is. This means you can do math on them, and a lot of software does just that, for good or bad.

>
l7@l7-virtual-machine:~/l7_learn_C/code$ ./ex9
numbers: 0 97 -609393408 -133402676
name each: a    #
name: a
numbers : 1 6960972 3 4
name each: L 7 j  
name: L7j
another: L7j
another each: L 7 j 
*** stack smashing detected ***: <unknown> terminated
Aborted (core dumped)
l7@l7-virtual-machine:~/l7_learn_C/code$ vim ex9.c
l7@l7-virtual-machine:~/l7_learn_C/code$ 



There’s also two syntaxes for doing a string: char name[4] = {'a'} on line 6 vs. char *another = "name"on line 44. The first one is less common and the second is what you should use for string literals like this.

