# Chapter 8-15 #

On the variable, array, looping concept

## exercise 11

In a function, 

>> #include<stdio.h> 
>>
>> int main(int argc, char *argv[])
>> {
>>
>>   while(i<argc)
>> 
>> printf("arg %d: %s\n",i,argv[i])
>>   }
   
   
## exercise 12

**If else-if, else and booliean

## exercise 13

**Switch statement

> The *switch-statement* is actually entirely different and is really a "jump table".Instead of random boolean
expressions, you can only put expressions that result in integers, and these integers are used to calculate jumps
from the top of the switch to the part that matches that value. 

Q:
> if-statement at the top that exits with a return 1; when you don’t give enough
arguments. Doing a return that’s not 0 is how you indicate to the OS that the program had an error. Any value
that’s greater than 0 can be tested for in scripts and other programs to figure out what happened.

Don't quite understand the function of *return* statement. Why we add return 1, after if statement?

