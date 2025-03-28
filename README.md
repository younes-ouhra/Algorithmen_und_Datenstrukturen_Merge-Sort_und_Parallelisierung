# Merge-Sort and Parallelization
## About
This project was built along with the Laboratory Algorithms and Data Structures at the Technical University of Applied Sciences of Regensburg, Bavaria, Germany. Also, it simulates the Merge-Sort with and without the parallelization, and measures the time-complexity for different concepts (functions) of Merge-Sort.

* <b>The mergesort-Function</b>: This function is about merge-sorting the elements recursivlly.
* The simplemerge-Function: This function sorts two already-sorted list of elements and merge them to a new result list.
* The pmerge-Function: This Function gets two different lists of elements and has the concept of threat each list separately by inserting each element of a list in the right position of the result list. For that reason the function calls the two functions qualabove and equalbelow.

  <a><img src = "Improved and parallelizable merge through rank determination.png"></a>

* The p2merge-Function: For the implementation of this Function, the number of execution units in the computer (in the program as the variable P2mergeThreads) is so important, because the two sorted lists of elements should be divided to the number of execution units (P2mergeThreads). Afterwards, every Sublist from the first list should be merged-sorted with a Sublist of the second list.
