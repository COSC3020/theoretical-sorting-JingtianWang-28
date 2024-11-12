# Theoretical Sorting

A Computer Science researcher claims to have come up with a sorting algorithm
that can sort arbitrary elements in $O(n)$ time based on comparisons of two
elements at a time. This would be asymptotically faster than any known general
sorting algorithm. The algorithm itself is proprietary and will be sold by a
company.

How would you verify this claim? You may assume that you have access to a
black-box implementation of the sorting algorithm, i.e. you cannot examine the
source code, but you can use it to sort any list you like. Explain in detail
your method for investigating whether X is correct, including any expected
results you would get.

Also give a theoretical argument for why X could or could not be correct, based
on the complexity of the general sorting problem we covered in class.

Add your answers to this markdown file.

///

Use ordered and unordered arrays and arrays of various situations, and choose arrays of different lengths

Compared to the known O(nlogn) sorting algorithm, the execution time will grow faster for the same input.

If this algorithm has O(n) time complexity, the execution time should grow linearly as n grows according to the size of the array.

If it deviates from the trend, it may prove to be a failure.

Based on the decision tree model of sorting, each comparison has two possible results, and sorting n elements requires at least log(n!) or nlogn comparisons.

Based on the known information of the current algorithm, any general sorting requires at least nlogn information to distinguish the sorting of n elements in the worst case, so at least omega(nlogn) comparisons are required.

In summary, unless it is best case time complexity, this algorithm may be wrong

###
Source:https://en.wikipedia.org/wiki/Sorting_algorithm

Plagiarism Statement: “I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice
