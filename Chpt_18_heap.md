# heap and stack allocation memory

After I typing everything on this exercise, and compiled successfully with no errors.
The thing drives me cary is that when I try to run the program, only got the message "Error memory".
And that is the bug the author set in *line 118* . Even with the instruction , how to break it.
I just can't find the way to fix it. It is something about the function *strncpy*.
I believe the next step is to study more about that function, then try something, after that ,
if stil remains the problem, then I will go directly to the other exercise, then one day I will come back.

>There is a bug in this program because of strncpy being poorly designed. Go read about strncpy then try
>to find out what happens when the name or address you give is greater than 512 bytes. Fix this by simply
>forcing the last character to '\0' so that it’s always set no matter what (which is what strncpy should do).

## Main idea

The main concept of this chapter is to introduce two ways of allocat memory: **heap** and **stack**.
