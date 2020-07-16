# Numpy

![](https://repository-images.githubusercontent.com/280190711/e6de8f80-c7a8-11ea-92bd-0e38b0acb258)



## Numpy (short for 'Numerical Python'): 
* It is the fundamental (but not the only) package required for high performance scientific computing and data analysis
* NumPy introduces and makes extensive use of the ndarray (nth-dimensional array) type, which is a homogeneous multidimensional array: it is a table of elements (usually numbers), all of the same type, indexed by a tuple of positive integers.
* It offers standard mathematical functions for fast operations on entire arrays of data without having to write loops ('array oriented computing')


A common question is **why we do we need the ndarray object since we can do the same operations with lists?**

> * **Speed of code execution:** A list is a flexible collection of various objects (integers, floats, strings, other objects, etc.). This flexibility however requires system memory and time for implementing various processes necessary for list construction and management. An array instead is a much more compact (although less flexible) object minimizing the code execution time and required system memory.
> * **Vectorization:** arrays are equipped with lots of functions that support vectorization, which is the ability to apply operations (addition, multiplication, etc.) on entire arrays instead of single numbers (scalars). Thus, many operations that would require loops if using lists are expressed in one single line of code with numpy arrays.
