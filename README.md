## Purpose of the Project
- Implement and time sorting algorithms in Python
- Calculate sorting algorithm runtimes using Big-O notation
- Compare theoretical runtimes with observed runtimes
- Test corner cases for each sorting algorithm
## Files Included
### ArraysForComparison.ipynb
- Create eight arrays of varying length that are sorted by each sorting algorithm
### ArraysForCornerCases.ipynb
- Create arrays used to check each sorting algorithm's performance when given arrays that are not positive integers
### ArraysForQuicksort.ipynb
- For each of the eight varying lengths, create six arrays that are sorted by Probabilistic Quicksort
- Multiple arrays of each length are needed to get multiple data points since Probabilistic Quicksort randomly chooses a pivot
### ArraysForQuickSortCornerCases.ipynb
- Create arrays to check Probabilistic Quicksort's performance when given arrays that are not positive integers
### CIandSETemplate.ipynb
- Gives Confidence Interval and Standard Error interpretation
### BubbleSortFinal.ipynb
- Theoretical and observed runtimes are similar since mean squared error is 0.006096488
- Time complexity of Bubble Sort is O(n^2)
### BubbleSortCornerCases.ipynb
- Arrays with unusual lengths or data types
	- Successful sorting: array of length 0, array of length 1, array with negative numbers, array with decimals, array of letters, array of strings
	- Failed sorting: array with string
- Arrays with different structures
	- Fastest runtime for equal elements and elements in ascending order
	- Slowest runtime for elements in descending order
### HeapSortFinal.ipynb
- Theoretical and observed runtimes are similar since mean squared error is 0.000001092
- Time complexity is O(nlog(n))
### HeapSortCornerCases.ipynb
- Arrays with unusual lengths or data types
	- Successful sorting: array of length 0, array of length 1, array with negative numbers, array with decimals, array of letters, array of strings
	- Failed sorting: array with string
- Arrays with different structures
	- Fastest runtime for equal elements
	- Slowest runtime for elements in descending order
### InsertionSortFinal.ipynb
- Theoretical and observed runtimes are similar since mean squared error is 0.003614408
- Time complexity is O(n^2)
### InsertionSortCornerCases.ipynb
- Arrays with unusual lengths or data types
	- Successful sorting: array of length 0, array of length 1, array with negative numbers, array with decimals, array of letters, array of strings
	- Failed sorting: array with string
- Arrays with different structures
	- Fastest runtime for equal elements and elements in ascending order
	- Slowest runtime for elements in descending order
### MergeSortFinal.ipynb
- Theoretical and observed runtimes are similar since mean squared error is 0.000004666
- Time complexity is O(nlog(n))
### MergeSortCornerCases.ipynb
- Arrays with unusual lengths or data types
	- Successful sorting: array of length 1, array with negative numbers, array with decimals, array of letters, array of strings
	- Failed sorting: array of length 0, array with string
- Arrays with different structures
	- Fastest runtime for array with equal elements
	- Slowest runtime for array in descending order
### QuickSortProbabilisticFinal.ipynb
- Mean squared error of the equation for the worst time complexity is 0.001923786
- Mean squared error of the equation for the expected run time is 0.002120841
- Worst case is O(n^2)
- Expected run time is O(nlog(n))
### QuickSortCornerCases.ipynb
- Arrays with unusual lengths or data types
	- Successful sorting: array of length 0, array of length 1, array with negative numbers, array with decimals, array of letters, array of strings
	- Failed sorting: array with string
- Arrays with different structures
	- Fastest runtime for elements with different ones place
	- Slowest runtime for equal elements
### RadixSortFinal.ipynb
- Theoretical and observed runtimes are similar since mean squared error is 0.000002648
- Time complexity is O(n)
### RadixSortCornerCases.ipynb
- Arrays with unusual lengths or data types
	- Successful sorting: array of length 1
	- Failed sorting: array of length 0, array with negative numbers, array with decimals, array with string, array of letters, array of strings
- Arrays with different structures
	- Fastest runtime for equal elements
	- Slowest runtime for different ones place
### SelectionSortFinal.ipynb
- Theoretical and observed runtimes are similar since mean squared error is 0.016570244
- Time complexity is O(n^2)
### SelectionSortCornerCases.ipynb
- Arrays with unusual lengths or data types
	- Successful sorting: array of length 0, array of length 1, array with negative numbers, array with decimals, array of letters, array of strings
	- Failed sorting: array with a string
- Arrays with different structures
	- Fastest runtime for array of equal elements
	- Slowest runtime for array in descending order
## Analysis
- Radix Sort sorts arrays the fastest
	- However, radix sort fails for all corner cases except sorting an array of length 1
- Merge Sort and Heap Sort also sort arrays quickly, and they successfully sort more corner cases than Radix Sort
- Bubble Sort and Selection Sort slowly sort arrays
## Conclusion
- When choosing a sorting algorithm, one must consider structure of arrays needing sorting, time complexity, and space complexity
