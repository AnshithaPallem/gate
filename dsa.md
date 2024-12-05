# Data Structure
A data structure is a storage that is used to store and organize data. It is a way of arranging data on a computer so that it can be accessed and updated efficiently.It is also used for processing, retrieving, and storing data.

![image](https://github.com/user-attachments/assets/f4be384b-43b8-4557-adfc-c404cf619f93)

**1. Linear Data Structure:** Data structure in which data elements are arranged sequentially or linearly, where each element is attached to its previous and next adjacent elements, is called a linear data structure. 

**Example:** Array, Stack, Queue, Linked List, etc.

**2. Static Data Structure:** Static data structure has a fixed memory size. It is easier to access the elements in a static data structure. 

**Example:** array.

**3. Dynamic Data Structure:** In dynamic data structure, the size is not fixed. It can be randomly updated during the runtime which may be considered efficient concerning the memory (space) complexity of the code. 

**Example:** Queue, Stack, linked list.

**4. Non-Linear Data Structure:** Data structures where data elements are not placed sequentially or linearly are called non-linear data structures. In a non-linear data structure, we can’t traverse all the elements in a single run only. 

**Examples:** Trees and Graphs.

# Array
Array is a linear data structure that stores a collection of elements of the same data type. Elements are allocated contiguous memory, allowing for constant-time access. Each element has a unique index number.

![Screenshot 2024-12-05 120035](https://github.com/user-attachments/assets/373b251a-dd92-462d-94bd-79361fe1bc77)

## Declaration of Array
arr = []

## Initialization of Array
arr = [1, 2, 3, 4, 5]

arr = ['a', 'b', 'c', 'd', 'e']

arr = [1.4, 2.0, 24.0, 5.0, 0.0] 

## Types of Arrays
### Types of Arrays on the basis of Size:
### 1. Fixed Sized Arrays:

We cannot alter or update the size of this array. Here only a fixed size (i,e. the size that is mentioned in square brackets []) of memory will be allocated for storage. In case, we don’t know the size of the array then if we declare a larger size and store a lesser number of elements will result in a wastage of memory or we declare a lesser size than the number of elements then we won’t get enough memory to store all the elements. In such cases, static memory allocation is not preferred.

**Ex:** 

arr = [0] * 5

print(arr)

### 2. Dynamic Sized Arrays:

The size of the array changes as per user requirements during execution of code so the coders do not have to worry about sizes. They can add and removed the elements as per the need. The memory is mostly dynamically allocated and de-allocated in these arrays.

arr = []

### Types of Arrays on the basis of Dimensions:
**1. One-dimensional Array(1-D Array):** You can imagine a 1d array as a row, where elements are stored one after another.

![Screenshot 2024-12-05 121248](https://github.com/user-attachments/assets/f55f3107-e231-49ff-9667-a953413dd269)

**2. Multi-dimensional Array:** A multi-dimensional array is an array with more than one dimension. We can use multidimensional array to store complex data in the form of tables, etc. We can have 2-D arrays, 3-D arrays, 4-D arrays and so on.

**Two-Dimensional Array(2-D Array or Matrix):** 2-D Multidimensional arrays can be considered as an array of arrays or as a matrix consisting of rows and columns.

![Screenshot 2024-12-05 121440](https://github.com/user-attachments/assets/c41e7807-35b7-46fa-9205-51bf839a2604)

**Three-Dimensional Array(3-D Array):** A 3-D Multidimensional array contains three dimensions, so it can be considered an array of two-dimensional arrays.

![Screenshot 2024-12-05 121519](https://github.com/user-attachments/assets/a4dcfad6-fa67-49a8-a7a6-a933c2f64e46)


