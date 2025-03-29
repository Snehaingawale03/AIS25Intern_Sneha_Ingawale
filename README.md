# AIS25Intern_Sneha_Ingawale
Python task 1
 1. Numbers in Python then we have to use the different types of numbers (Integers, Floats, Complex numbers).
Perform basic arithmetic operations like addition, subtraction, multiplication, and division.

2. Operators in Python then we have to use the arithmetic, comparison, logical, and assignment operators.
Perform operations such as addition, subtraction, comparison (==, !=, <, >), and logical operations (and, or).

3. Lists in Python
Then Perform the following methods on lists:
1) Accessing elements: Use indexing and slicing.
2) Modifying elements: Change the value of an element by index.
3) Adding elements: Use append(), insert().
4) Removing elements: Use remove(), pop(), or clear().
5) Other methods: Use sort(), reverse(), extend(), count(), index(), and copy().

4. Tuples in Python
then Perform the following methods on tuples:
Accessing elements: Use indexing and slicing.
Slicing: Extract a portion of the tuple.
Concatenation: Combine two tuples using +.
Repetition: Repeat a tuple using *.
Count: Count occurrences of an element with count().
Index: Find the index of an element using index().

5. Sets in Python operations (e.g., adding elements, removing elements, union, intersection, difference).
Perform methods like add(), remove(), union(), intersection(), difference().

6. Dictionaries in Python operations (e.g., accessing key-value pairs, adding, and removing items).
Perform methods like get(), keys(), values(), items(), pop(), update().

7. Common Python Errors
IndentationError: Explain the cause and show how to fix it.
NameError: Discuss the cause and provide a fix.
ValueError: Explain what causes this error and how to avoid it.
TypeError: Describe the reason for this error and how to handle it.
IndexError: Discuss the cause of accessing out-of-range indexes.
KeyError: Explain how accessing non-existent keys causes this error and ways to handle and then complet task 1

## Python task 2:

# Grade Code and Divisibility Check by using if ,if else and if elif else statement.
1. Grade Code: Assigns grades based on a given percentage.
2. Divisibility Check: Checks whether a number is divisible by 2 or 3.

# Grade Code
- Assigns grades based on the following criteria:
    - P: 50
    - O: p > 75
    - A: 60 < p < 75
    - B: 50 < p < 60
    - C: 35 < p < 50
    - Fail: p < 35
# Divisibility Check
- Checks whether a number n is divisible by 2 or 3.
To run the code, simply execute the Python files using
## For loop:
- Printing odd values between 20 and 80 without using if then by using for loop only.
- Creating lists of numbers using for loops
- Taking cube of odd values between 20 to 40
- Printing names and ages of friends
- Swapping first and last element of a list
- Counting length of a string
- Calculating sum of non-negative integers
- Calculating factorial

Each task has a separate code snippet, and the solutions are well-documented and easy to understand.
### While loop:
This repository contains solutions to various while loop tasks, including:

- Odd-Even number check
- Printing * pattern
- Creating a list of numbers from 1 to 20
- Creating a list of numbers from 20 to 1
- Using break control statement

Each task has a separate code snippet, and the solutions are well-documented and easy to understand in the task 2.

### Python task 3

### Python task 4:
# Task 4: Machine Learning with NumPy
1. Introduction to NumPy
NumPy (Numerical Python) is a library for working with arrays and mathematical operations in Python. It's essential for numerical computations, data science, machine learning, and scientific computing.

- Installation: pip install numpy
- Importance: NumPy provides support for large, multi-dimensional arrays and matrices, and is the foundation of most scientific computing in Python.

2. Arrays in NumPy
- ndarray (N-dimensional array): The core data structure in NumPy.
- Creating arrays:
    - np.array(): Creates an array from a Python list or other iterable.
    - np.zeros(): Creates an array filled with zeros.
    - np.ones(): Creates an array filled with ones.
    - np.arange(): Creates an array with evenly spaced values.
    - np.linspace(): Creates an array with evenly spaced values over a specified range.
- Array indexing and slicing:
    - Accessing elements: arr[index]
    - Slicing: arr[start:stop:step]
3. Array Operations
- Arithmetic operations:
    - Addition: arr1 + arr2
    - Subtraction: arr1 - arr2
    - Multiplication: arr1 * arr2
    - Division: arr1 / arr2
- Broadcasting:
    - Performing operations on arrays of different shapes.
    - Rules of broadcasting: matching dimensions, aligning axes.
- Element-wise operations and functions:
    - np.sqrt(): Square root.
    - np.sin(): Sine.
    - np.exp(): Exponential.

4. Array Shapes and Reshaping
- Checking array dimensions:
    - .shape: Returns the shape of the array as a tuple.
    - .ndim: Returns the number of dimensions in the array.
- Changing array shape:
    - .reshape(): Reshapes the array to a new shape.
    - .flatten(): Flattens the array to a 1D array.
    - .transpose(): Transposes the array.
- Concatenating and splitting arrays:
    - np.concatenate(): Concatenates arrays along a specified axis.
    - np.vstack(): Stacks arrays vertically.
    - np.hstack(): Stacks arrays horizontally.
    - np.split(): Splits an array into multiple sub-arrays.
5. Array Manipulation
- Indexing and slicing:
    - Multi-dimensional arrays.
- Masking (logical indexing):
    - Selecting elements based on conditions.
- Fancy indexing:
    - Using arrays of indices to select elements.

6. Mathematical Functions
- Universal functions (ufuncs):
    - np.add(): Addition.
    - np.subtract(): Subtraction.
    - np.multiply(): Multiplication.
    - np.divide(): Division.
- Statistical functions:
    - np.mean(): Mean.
    - np.median(): Median.
    - np.std(): Standard deviation.
    - np.var(): Variance.
    - np.min(): Minimum.
    - np.max(): Maximum.
- Linear algebra functions:
    - np.dot(): Dot product.
    - np.matmul(): Matrix product.
    - np.linalg.inv(): Matrix inverse.
    - np.linalg.eig(): Eigenvalues and eigenvectors.
 7. Random Number Generation
- Generating random numbers:
    - np.random.rand(): Random numbers in a specified shape.
    - np.random.randint(): Random integers in a specified range.
- Seeding random number generation:
    - np.random.seed(): Sets the seed for the random number generator.
- Random sampling, shuffling, and permutations:
    - np.random.choice(): Randomly selects elements from an array.
    - np.random.shuffle(): Shuffles the elements of an array.
    - np.random.permutation(): Returns a randomly permuted array.
8. Broadcasting
- Understanding how NumPy handles operations between arrays of different shapes.
- Rules of broadcasting:
    - Matching dimensions.
    - Aligning axes.


  ### Python task 5:
# Key Data Structures
1. Series: 1D labeled array, similar to a list with index labels.
2. DataFrame: 2D labeled table, similar to an Excel spreadsheet.

# Creating Data Structures
1. pd.Series(): Create a Series from a list or array.
2. pd.DataFrame(): Create a DataFrame from a dictionary or list of lists.

# Data Operations
Indexing & Slicing
1. df['col']: Select a column by label.
2. df.iloc[]: Select rows and columns by integer position.
3. df.loc[]: Select rows and columns by label.

Data Cleaning
1. .isnull(): Check for missing values.
2. .dropna(): Remove rows or columns with missing values.
3. .fillna(): Replace missing values with a specified value.

Renaming
1. df.rename(): Rename columns or index labels.

Filtering
1. df[df['col'] > value]: Select rows where a condition is true.

Aggregation and Grouping
1. df.groupby('col'): Group a DataFrame by a column.
2. .sum(), .mean(), .count(): Perform aggregation operations.

Merging and Joining
1. pd.merge(): Merge two DataFrames based on a common column.
2. df.concat(): Concatenate two DataFrames.

File I/O
1. pd.read_csv(): Read a CSV file into a DataFrame.
2. df.to_csv(): Write a DataFrame to a CSV file.
3. pd.read_excel(): Read an Excel file into a DataFrame.
4. df.to_excel(): Write a DataFrame to an Excel file.

Time Series
1. pd.to_datetime(): Convert a column to datetime format.
2. .resample(): Resample a time series DataFrame.

Visualization
1. df.plot(): Create a basic plot of a DataFrame.

Condition Selection
1. And: Select rows where multiple conditions are true.
2. Or: Select rows where at least one condition is true.

📖 Project Overview:
This project is a Retrieval-Augmented Generation (RAG) chatbot that allows users to upload PDF documents and receive AI-generated responses based on the document’s content. It leverages FAISS for efficient vector search and Hugging Face models for natural language understanding and response generation.

🚀 Key Features:
PDF-Based Q&A: Users can upload PDFs, and the chatbot retrieves relevant information.

AI-Powered Responses: Uses Flan-T5/GPT models for generating responses.

Efficient Retrieval: Implements FAISS (Facebook AI Similarity Search) for fast and accurate document retrieval.

Interactive UI: Built using Streamlit for a seamless user experience.

🛠️ Technologies Used:
Python

LangChain (for RAG pipeline)

Hugging Face Models (Flan-T5, GPT, etc.)

FAISS (Vector Database for document retrieval)

Streamlit (User Interface)

PyMuPDF, pdfminer.six (PDF Processing)
