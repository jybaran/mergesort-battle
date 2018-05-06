# mergesort-battle
Cathy Lee, Jenny Baran, and Zoe Riell
CSC 220

We created 7 dictionaries to store the runtimes of 4 different sorts based on 7 different outputs (10^k, k = 1, 2, ..., 7). We compared the built-in Python and Julia sort functions with iterative implementations by hand.

The default built-in Julia sort, .sort(), uses Quick Sort for numeric arrays and Merge Sort for other arrays. It does not call a lower level language.

The built-in Python sort, .sorted(), uses Timsort, which is a hybrid sorting algorithm derived from Merge Sort and Insertion Sort. It is written in C.

In our performance comparisons, Python's built-in sort consistently had the longest runtime, while Julia's built-in sort consistently had the shortest. As for the by-hand implementations, the Merge Sort function written in Julia performed better asymptotically (noticeable when k = 6, 7).