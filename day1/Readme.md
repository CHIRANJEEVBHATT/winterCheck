Sorting in arrays

Bubble Sort is a simple sorting algorithm that arranges elements in the correct order by repeatedly comparing two adjacent values and swapping them if they are in the wrong order
time complexity O(n^2)

Selection Sort is a sorting algorithm that finds the smallest element from the unsorted part of the list and places it at the beginning
time complexity O(n^2)

Insertion Sort works by assuming the first element as sorted and then inserting each next element into its correct position in the sorted portion of the array
time complexity O(n^2)

DNF algorithm
we divide the array into three regions called low, mid, and high. We start by assuming the beginning part of the array as the correct region for 0s and then traverse the array using three pointers. At each step, the current element is checked. If the element is 0, it is swapped into the low region and both low and mid pointers are moved forward. If the element is 1, only the mid pointer is increased. If the element is 2, it is swapped with the high region and the high pointer is decreased. In this way, the array is sorted into three groups consisting of 0s, 1s, and 2s in a single pass without using any extra space.

question is leet code 75 sort colors
time complexity O(n)

MERGE 2 SORTED ARRAY 
we are given two sorted arrays where the first array has enough extra space at the end to store all elements of the second array instead of using an extra array we merge both arrays directly into the first one we start comparing elements from the end of both arrays  pointer is placed at the last valid element of the first array another at the last element of the second array, and a third pointer at the very end of the first array.

At each step we compare values from both arrays and place the larger one at the last position of the first array then we move the pointer accordingly this process continues until all elements from the second array are inserted
