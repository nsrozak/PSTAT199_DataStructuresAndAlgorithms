## Purpose of the Project
- Implement and time sorting algorithms in Python
- Calculate sorting algorithm runtimes using Big-O notation
- Compare theoretical runtimes with observed runtimes
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
	- Fastest runtime for equal elements and elements in ascending order (6 seconds)
	- Slowest runtime for elements in descending order (16 seconds)
### HeapSortFinal.ipynb
- Theoretical and observed runtimes are similar since mean squared error is 0.000001092
- Time complexity is O(nlog(n))
### HeapSortCornerCases.ipynb
- Arrays with unusual lengths or data types
	- Successful sorting: array of length 0, array of length 1, array with negative numbers, array with decimals, array of letters, array of strings
	- Failed sorting: array with string
- Arrays with different structures
	- Fastest runtime for equal elements (0.01 seconds)
	- Slowest runtime for elements in descending order (0.11 seconds)
### InsertionSortFinal.ipynb
- Theoretical and observed runtimes are similar since mean squared error is 0.003614408
- Time complexity is O(n^2)
### InsertionSortCornerCases.ipynb
- Arrays with unusual lengths or data types
	- Successful sorting: array of length 0, array of length 1, array with negative numbers, array with decimals, array of letters, array of strings
	- Failed sorting: array with string
- Arrays with different structures
	- Fastest runtime for equal elements and elements in ascending order (almost 0 seconds)
	- Slowest runtime for elements in descending order (17.5 seconds)
### MergeSortFinal.ipynb
- Theoretical and observed runtimes are similar since mean squared error is 0.000004666
- Time complexity is O(nlog(n))
### MergeSortCornerCases.ipynb
- Arrays with unusual lengths or data types
	- Successful sorting: array of length 1, array with negative numbers, array with decimals, array of letters, array of strings
	- Failed sorting: array of length 0, array with string
- Arrays with different structures
	- Fastest runtime for array with equal elements (0.05 seconds)
	- Slowest runtime for array in descending order (0.07 seconds)
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
	- Fastest runtime for elements with different ones place (0.025 seconds)
	- Slowest runtime for equal elements (0.2 seconds)
### RadixSortFinal.ipynb
- Theoretical and observed runtimes are similar since mean squared error is 0.000002648
- Time complexity is O(n)
### RadixSortCornerCases.ipynb
- Arrays with unusual lengths or data types
	- Successful sorting: array of length 1
	- Failed sorting: array of length 0, array with negative numbers, array with decimals, array with string, array of letters, array of strings
- Arrays with different structures
	- Fastest runtime for equal elements (0.01 seconds)
	- Slowest runtime for different ones place (0.07 seconds)
### SelectionSortFinal.ipynb
- Theoretical and observed runtimes are similar since mean squared error is 0.016570244
- Time complexity is O(n^2)
### SelectionSortCornerCases.ipynb
- Arrays with unusual lengths or data types
	- Successful sorting: array of length 0, array of length 1, array with negative numbers, array with decimals, array of letters, array of strings
	- Failed sorting: array with a string
- Arrays with different structures
	- Fastest runtime for array of equal elements (4.2 seconds)
	- Slowest runtime for array in descending order (4.8 seconds)
