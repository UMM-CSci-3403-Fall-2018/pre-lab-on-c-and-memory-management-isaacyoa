# Leak report
I was able to find the leak by using the valgrind command that showed the data on how much memory was leaked.

In the leak summary it is reported that there is 46 bytes in 6 blocks lost. To fix this I need to free the code.



_Use this document to describe whatever memory leaks you find in `clean_whitespace.c` and how you might fix them. You should also probably remove this explanatory text._

