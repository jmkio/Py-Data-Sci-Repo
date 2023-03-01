## Python 101:Introduction to Python for Data Science

Python is a popular high level programming language used in various fields, including data analysis.
It has a simple and easy to learn syntax, making it a popular language among beginners and experienced alike.
Python is supported by a large community and has numerous open source libraries that make it ideal for data analysis.
Python libraries are collections of pre-written code that make certain tasks easier to perform.
Data analysis is essential in many industries including finance, marketing, healthcare and many more.
In this article, we will explore some of the essential concepts of Python for data analysis, including Python libraries, how to install Python for Windows, Python data types, Python data structures, Python functions, and Python programming basics.
**

## LIBRARIES

Python's popularity in data science is due to its powerful and popular libraries. These libraries provide a set of tools and functions that make it easier to work with data and perform analysis tasks.
**Some of the popular libraries for data analysis are:**

**1. NumPy**
This is a python library used for numerical computations. It provides tools for creating and manipulating large and multi-dimensional arrays and matrices, hence making it useful for scientific computing and data analysis. NumPy has a comprehensive set of mathematical functions for linear algebra, Fourier transforms and random number generation.

**2. Pandas**
Pandas is a library for data manipulation and analysis. It does this by providing a set of functions for reading, group filter, reshaping, writing and processing tabular data. This makes Pandas useful for exploratory data analysis as well as easy to work with large datasets.

**3. MatplotLib**
This is Python's visualization library. It provides tools for creating different types of charts and plots such as bar charts, live graphs, histograms, heat maps and scatter plots. This makes for static, animated and interactive visualization of data.

**4. Seaborn**
This is a visualization library based on MatplotLib. It provides tools for creating complex visualization, such as heat maps, scatter plots, box plots, violin plots and pair plots. It is useful for creating publication quality visualizations.

**5. SciPy**
SciPy is built on NumPy. It is a library for scientific computing and technical computing. It is essential for scientific and engineering applications as it provides a set of tools and functions for optimization, integration, linear algebra and signal processing.

**6.Scikit Learn**
This is a Python library used for machine learning. It provides tools for building and evaluating machine learning models in Python.
Scikit has algorithms for classification, regression and clustering, which makes it a simple and efficient tool for data mining and data analysis.
**

## How To Install Python For Windows

**
To install Python on Windows, you can follow these steps:

- Go to the official Python website: <https://www.python.org/downloads/>
- Click on the "Download Python" button. This will take you to a page with the latest versions of Python.
- Choose the appropriate version of Python for your Windows operating system. If you're not sure which version to download, you can go with the latest version, which should work for most Windows systems.
- Once you've downloaded the installation file, double-click on it to start the installation process.
- Follow the installation wizard prompts. You can usually accept the default options for most of the prompts.
- When the installation is complete, you can test that Python is installed correctly by opening a Command Prompt window and typing "python" (without the quotes) at the command prompt. If Python is installed correctly, you should see the Python version number displayed.
That's it! You've successfully installed Python on your Windows computer.
**

## Python Data Types and Structures

Python has several built in data types:

**1. Numbers**
In Python, numbers are represented by three types: integers, floating-point numbers, and complex numbers. Integers are whole numbers with no decimal points, while floating-point numbers have decimal points. Complex numbers are made up of a real part and an imaginary part, and they are denoted using the "j" suffix.
For Example: _Integers_

`my_integer = 42
print(my_integer)
42`
Example: _Float_

`price = 9.99
print(price)
9.99`

**2. Strings**
Strings are sequences of characters enclosed in single or double quotes. They are used to represent text data. Python allows various operations on strings, such as concatenation, slicing, and formatting.
For example:
`message = "Hello, world!"
print(message)
"Hello, world!"`

**3. Lists**
Lists are ordered collections of elements, which can be of different data types. They are denoted using square brackets and can be modified after creation. Python allows various operations on lists, such as appending, removing, and slicing.
For example:

`numbers = [1, 2, 3, 4, 5]
print(numbers)
[1, 2, 3, 4, 5]`

**4. Tuples**
Tuples are similar to lists in that they are ordered collections of elements. However, unlike lists, tuples are immutable, which means that their elements cannot be modified once they are created. Tuples are denoted using parentheses.
For example:

`fruits = ("apple", "banana", "orange")
print(fruits)
('apple', 'banana', 'orange')`

**5. Sets**
Sets are unordered collections of unique elements. They are denoted using curly braces and can be modified after creation. Python allows various operations on sets, such as union, intersection, and difference.
For example:

`numbers = {1, 2, 3, 4, 5}
print(numbers)
{1, 2, 3, 4, 5}`

**6. Dictionaries**
Dictionaries are collections of key-value pairs, where each key is associated with a value. They are denoted using curly braces and can be modified after creation. Python allows various operations on dictionaries, such as adding, deleting, and updating key-value pairs.
For example:
`person = {"name": "John", "age": 35, "city": "Nairobi"}
print(person)
{'name': 'John', 'age': 35, 'city': 'Nairobi'}`

**7.Booleans**
Boolean data types are a type of data that represents a logical value. In Python, the two Boolean values are **'True'** and **'False'**. Boolean values are often used in control structures, such as **'if'** statements, to determine which branch of code should be executed.
Example of comparison of two values:

`x = 10
y = 5
result = x > y
print(result) # True`

`x = 5
y = 10
result = x > y
print(result) # False
