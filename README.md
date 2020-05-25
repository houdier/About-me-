##Binary Search

Binary search is a way to locate a element in a **sorted** sequence. Here is how it works. 

Assume the sequence is strictly ascending. The middle element in the sequence separates the sequence into two subsequences —— the left 
half and the right half. In each search, compare the target element with the middle element of the subsequence. If the element is equal two the middle element, 
the element is located and the search is done. If the element is smaller than the middle element, go on comparing the target with the middle element of the left half. 
If the element is larger than the middle element, go on comparing the target with the middle element of the right half. Repeat this act until the element is located or, if the target element doesn't
exist in the sequence, repeat until there's only one element in the subsequence. 
