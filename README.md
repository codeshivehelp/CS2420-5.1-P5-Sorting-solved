# CS2420-5.1-P5-Sorting-solved

Download Here: [CS2420 5.1 P5 – Sorting solved](https://jarviscodinghub.com/assignment/5-1-p5-sorting-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Sorting Algorithms
Purpose
to familiarize you with:
• Sorting Algorithms
• Recursion
• Analysis
The purpose of this lab is to demonstrate the speed difference between sorting arrays of random integers using:
• Quick-Sort
• Merge-Sort
• Insertion Sort
• SelectiorrSort
• Built-in Sort ot an array (from €algorilhm>)
This difference will not show if the array size is too small, Therefore, you should make your array as large as possible (without having it take
too long), ar•d still have 2 signifcant dgits of output lor each search. Quick and Merge are much faster than Insertion and Selection. You
also need to re•randomize each time to give accurate results for each sort,
Lastly, you will use the to sort the array. This part should be easy and fast! A good example of how to do this is at
httpi//wwwcpluspLscorn/ar1icles/NhAORXSz/
Tasks
• Create a Sort Class
• Mernber variables
dynamic array of integers
o size of
• Constructor(array size)
• Destructor
• A function to get the size Of the array
o int GetSize() const
• A function to return the array Of integers
o int const
• A function to intiaJize the array with random integers
o ved InitArray():
use the same seed before each array initialization, so the array is always the same
• Selection Sort of the array data
a ved SelectionSort();
• Insertion Sort of the array data
void InsertionSort();
Merge Sort of the array data
void MergeSort();
Quick Sort of the array data
o ved QuickSort():
a Quick Sort and partition should be separate functions.
o With QuickSortO calling partition()
• (should be one line of code)
o ved AlgorithmSortO;
http:f/en.cppreference.com/w/cpp/algorithm/sort

• You will also need several helper functions.
o These should be private.
o void MergeSortRecursionHelper(intindexl, intindexK);
o void QuickSortRecursionHeIper(intinitialLowIndex, intinitialHighlndex);
Create a non-interactive driver that runs each of these sorts and times and displays the outputs.
starting SelectionSort
Selection Sort duration:
starting InsertionSort
Insertion Sort duration:
10821ms .
11459ms .
starting MergeSort
erge Sort duration:
starting QuickSort
uick Sort duration:
starting std: : sort()
246ms .
210ms .
std: : sort() duration of: 164ms.
• Use the provided Timer.cpp and Timerh as you did in the Search Project to time these sorts. Again, adjust the size of the array so that
you have at least two significant digits of time data.
