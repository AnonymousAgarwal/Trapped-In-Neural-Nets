# Welcome to a more detailed basic python tutorial

## Installation and Setup 
Visit this link for a detailed guide on installing and setting up Python - [Python Installation and Setup](https://wiki.python.org/moin/BeginnersGuide/Download)

## Introduction to Jupyter Notebooks
Jupyter notebook is a web based notebook environment which is widely used for interactive programming, that is, code execution combined with rich markdown text and much more. The Jupyter notebook runs a local Ipython kernel on your machine and launches in your web browser. These notebooks are also called as Ipython notebooks, and have a '.ipynb' extension instead of traditional '.py' extension for Python files. 
The assignments in this course are made in Jupyter notebooks. Hence, it is important for you to get aquainted with them.

Visit this link for installing and setting up a basic notebook - [Setting up Jupyter Notebook](https://realpython.com/jupyter-notebook-introduction/). The link also teaches you to write and execute a basic Python code in a Notebook cell. 

## Introduction to Data Types and Data Structures in Python
Once you have set up the environment for writing your code, we now begin with coding in Python. Let's get started. 

Head over to this link - [Introduction to Python Data Types](https://www.learnpython.org/en/Welcome) and start with the topics in the 'Learn the Basics' sections one by one (till 'Basic String Operations'). These are official tutorials from the Python organisation which are well curated for beginners and contain an inbuilt Ipython shell for writing and executing your code there itself. 

If you are not of the reading kind, checkout the video tutorial series in the Week1's README.md

You can also read these concepts from GeeksForGeeks. They explain each concept in good detail along with examples. 

Irrespective of where you choose to read/watch from, you should be familiar with the following topics:
* [Strings](https://www.geeksforgeeks.org/python-strings/?ref=lbp)
* [Lists](https://www.geeksforgeeks.org/python-list/?ref=lbp)
* [Tuples](https://www.geeksforgeeks.org/python-tuples/?ref=lbp)
* [Sets](https://www.geeksforgeeks.org/python-sets/?ref=lbp) 
* [Dictionary](https://www.geeksforgeeks.org/python-dictionary/?ref=lbp)
* [Arrays](https://www.geeksforgeeks.org/python-arrays/?ref=lbp)

## Operators in Python 
Now that you have a basic idea about different variable data types and data structures, let us now explore how you can work with multiple variables at once in order to get your desired output. This is done using Operators. 

Operators in a programming language mean the same thing as operators in maths (almost), so the only thing you need to be concerned about is the syntax of working with operators. 

Head over to this link - [Python Operators](https://www.geeksforgeeks.org/python-operators/?ref=lbp) for a detailed description of different operators in Python. Then check out the tabs in the navigation bar on the left and read about all the operators one by one. 
<br>These are extremely important as some of the concepts explained here will be used to define other concepts later on, and to understand any piece of code analytically, you should know what each line of code is doing. 
<br>You should be familiar with the following Python operators:
* Arithmetic Operators
* Relational Operators
* Logical Operators
* Bitwise Operators 
* Assignment Operators
* Identity Operators
* Membership Operators

## Conditions And Loops 
Conditions and Loops are a core part of any program written in any programming language. You use loops whenever you want to perform a particular task repeatedly over many iterations, given a condition is satisfied. Conditions are also used without loops, as if-else conditions. 

Checkout this link for a detailed article on Conditions and Loops - [Conditions](https://www.learnpython.org/en/Conditions) and [Loops](https://www.learnpython.org/en/Loops)
<br> You can also refer to this link from GeeksForGeeks - [Conditions and Loops](https://www.geeksforgeeks.org/python-if-else/?ref=lbp) (Checkout all the tabs in the navigation bar on the left)
<br> Again, if you prefer videos instead, refer to this [Youtube Playlist's](https://www.youtube.com/playlist?list=PLzMcBGfZo4-mFu00qxl0a67RhjjZj3jXm) Tutorial #6, #7 and #9. 

Make sure you have covered the following topics - 
* For loop
* while loop
* break statement
* continue statement
* If-else condition ( normal, nested, if-elif)

# Learning with Hands-on code
Once you are done with the above topics, complete the Jupyter Notebooks:

* [Module 1](./Week1-Module1.ipynb)
* [Module 2](./Week1-Module2.ipynb)
* [Assignment 1](./Week1-Assignment.ipynb)

The content is divided into 2 modules. The first one covers Data Types and Operators, while the second one covers Conditionals and Loops. These interacive notebooks introduce you to basic concepts and syntax along with hands-on code to try yourself! Make sure to play around with the code to understand it well. Read the instructions below on how to download the notebooks.

### Instructions to download the assignments:
1. Open on the respective `.ipynb` file on GitHub
2. In the upper right corner, there are several buttons and icons including the ones shown below. Click on the Raw Button.
       Raw | Blame
      --- | ---
      
3. The python notebook opens as raw text in browser. Right click->Save as OR just press CTRL + S. Save the notebook, open it using Jupyter Notebook you just installed and start learning! 


___

## Python Functions

A function is a set of statements that take inputs, do some specific computation and produces output. The idea is to put some commonly or repeatedly done task together and make a function, so that instead of writing the same code again and again for different inputs, we can call the function.

This [Notebook](./Notebook1.ipynb) covers the most aspects of Python Functions. Download the Notebook and make changes to the code and see how they reflect in the output.

If you want to read more on functions, you can have a look at [this](https://www.geeksforgeeks.org/functions-in-python/) and [this](https://automatetheboringstuff.com/2e/chapter3/)

If you prefer watching a video tutorial, watch this [Youtube Playlist's](https://www.youtube.com/playlist?list=PLzMcBGfZo4-mFu00qxl0a67RhjjZj3jXm) #12 Tutorial.

### Scope of a Variable

Scope refers to the visibility of variables. In other words, which parts of your program can see or use it. Variables that are defined inside a function body have a local scope, and those defined outside have a global scope. This means that local variables can be accessed only inside the function in which they are declared, whereas global variables can be accessed throughout the program body by all functions

# Python Modules and Packages

This [Notebook](https://github.com/abhipaiangle/learners-space/blob/master/Python/Week%202/Notebook3.ipynb) covers most aspects of Python Modules and Packages. You may use Spyder/PyCharm for this but if you are using Google Colab, read the instructions given in the notebook.

To read more about Modules and Packages head over to [this](https://www.geeksforgeeks.org/python-modules/) and [this](https://www.learnpython.org/en/Modules_and_Packages)


# Some Standard Libraries of Python

In python, collection of predefined modules and packages is called a library. Here, we will learn about some of the standard library modules.

* **math** - The math module is used to access mathematical functions in the Python. All methods of this functions are used for integer or real type objects, not for complex numbers. Refer [this](https://docs.python.org/3/library/math.html) documentation for learning different functions of math.

* **random** - This module implements pseudo-random number generators for various distributions. Refer [this](https://docs.python.org/3/library/random.html) documentation of random module.

* **time** - This module provides various time-related functions. Refer [this](https://docs.python.org/3/library/time.html) documentation of time module.

* **datetime** - The datetime module supplies classes for manipulating dates and times. Refer [this](https://docs.python.org/3/library/datetime.html) documentation of time module.

## Introduction to Object Oriented Programming 
As the name suggests, Object-Oriented Programming or OOPs refers to languages that uses objects in programming. Object-oriented programming aims to implement real-world entities like inheritance, polymorphism etc in programming. The main aim of OOP is to bind together the data and the functions that operate on them so that no other part of the code can access this data except that function.

Head over to this link for a brief introduction on each of the topics listed above - **[Python OOP](https://www.programiz.com/python-programming/object-oriented-programming)** 

Now lets discuss each of the topics in detail - 

## Classes and Objects 
A class is a user defined blueprint or prototype from which objects are created. It represents the set of properties or **methods** that are common to all objects of one type. You can think of a class as a collection of many different functions and attributes (variables) that can be accessed by an object of that class. These methods inside a class are defined almost in the same way normal Python functions are defined, with a major difference being the 'self' argument and some special methods only found in a class body, for example:- the **'\_init_'** method, **'\_add_'** method, etc. 

An Object is a basic unit of Object Oriented Programming and a way to represent the classes you have declared in your program. And thus an object can also be sometimes called an instance of a class. Whenever you create an object of a class, you can access all the methods which you have declared in the body of the class. (Note that this is not possible in the case of Private classes (covered later)). 

You can check out any one of these detailed tutorials on Classes and Objects in Python based on your preference -
* **[Python Classes and Objects](https://www.learnpython.org/en/Classes_and_Objects)**
* **[Python Classes and Objects Detailed](https://www.programiz.com/python-programming/class)**
* Detailed Video Tutorials on Classes and Objects - **[Video #1](https://www.youtube.com/watch?v=v_Jp11xqCzg&list=PLzMcBGfZo4-l1MqB1zoYfqzlj_HH-ZzXt&index=2&t=0s)** and **[Video #2](https://www.youtube.com/watch?v=jQiUOV15IRI&list=PLzMcBGfZo4-l1MqB1zoYfqzlj_HH-ZzXt&index=2)** 

### Constructors and Destructors 
The special methods found in a class are related to another concept in OOP, known as Constructors and Destructors. A Constructor is a special function which is **automatically** called whenever a class object is created. Similarly, a Destructor is a special function which is automatically executed whenever a class object is destroyed, i.e, goes out of scope. By now you must know what the 'scope' of a variable means. 
<br> A constructor is unique to a class, and is represented using the **'\_init_'** method in a class. Similarly, a destructor is represented using the **'\_del_'** method in the class. 
* For more information, check out this video on - **[Constructors and Destructors](https://www.youtube.com/watch?v=NSssW0duUkQ)**

## File Handling 

Files are named locations on disk to store related information. They are used to permanently store data in a non-volatile memory (e.g. hard disk). Since Random Access Memory (RAM) is volatile (which loses its data when the computer is turned off), we use files for future use of the data by permanently storing them. When we want to read from or write to a file, we need to open it first. When we are done, it needs to be closed so that the resources that are tied with the file are freed.

Hence, in Python, a file operation takes place in the following order:
1. Open a file
2. Read or write (perform operation)
3. Close the file

Head over to this [Notebook](./File_Handling/Week5-1.ipynb) to learn about Python functions for fucntions for file handling.

To read more about File Handling refer [this](https://www.geeksforgeeks.org/file-handling-python/)

<hr>

## Use of Numpy

##### What is NumPy?
NumPy is a python library used for working with arrays. It also has functions for working in domain of linear algebra, fourier transform, and matrices. NumPy stands for Numerical Python. It is an open source project and you can use it freely.

##### Why Use NumPy ?
In Python we have lists that serve the purpose of arrays, but they are slow to process. NumPy aims to provide an array object that is up to 50x faster that traditional Python lists. The array object in NumPy is called ndarray, it provides a lot of supporting functions that make working with ndarray very easy. Arrays are very frequently used in data science, where speed and resources are very important.

(Data Science: is a branch of computer science where we study how to store, use and analyze data for deriving information from it.)

##### Why is NumPy Faster Than Lists?
NumPy arrays are stored at one continuous place in memory unlike lists, so processes can access and manipulate them very efficiently. This behavior is called locality of reference in computer science. This is the main reason why NumPy is faster than lists. Also it is optimized to work with latest CPU architectures.

Head on to this [link](https://www.edureka.co/blog/python-numpy-tutorial/) for a brief explanation of numpy methods. Another reference for those aready a bit familiar and looking for a quick recap is [here](https://towardsdatascience.com/a-quick-introduction-to-the-numpy-library-6f61b7dee4db).

<hr>

## Use of Pandas

Pandas is an open-source library that is made mainly for working with relational or labeled data both easily and intuitively. It provides various data structures and operations for manipulating numerical data and time series. This library is built on the top of the NumPy library. Pandas is fast and it has high-performance & productivity for users.

##### Advantages of using Python
* Fast and efficient for manipulating and analyzing data.
* Data from different file objects can be loaded.
* Easy handling of missing data (represented as NaN) in floating point as well as non-floating point data
* Size mutability: columns can be inserted and deleted from DataFrame and higher dimensional objects
* Data set merging and joining.
* Flexible reshaping and pivoting of data sets
* Provides time-series functionality.
* Powerful group by functionality for performing split-apply-combine operations on data sets.

Head on to this [link](https://www.edureka.co/blog/python-pandas-tutorial/) for an overview of the library. If you are looking for quick recap just look at the video included in the previous link. Another reference for a more comprehensive overview is provided [here](https://pandas.pydata.org/pandas-docs/stable/getting_started/10min.html).

<hr>

## Use of SciPy

SciPy is a collection of mathematical algorithms and convenience functions built on the NumPy extension of Python. It adds significant power to the interactive Python session by providing the user with high-level commands and classes for manipulating and visualizing data. With SciPy, an interactive Python session becomes a data-processing and system-prototyping environment rivaling systems, such as MATLAB, IDL, Octave, R-Lab, and SciLab.

The additional benefit of basing SciPy on Python is that this also makes a powerful programming language available for use in developing sophisticated programs and specialized applications. Scientific applications using SciPy benefit from the development of additional modules in numerous niches of the software landscape by developers across the world. Everything from parallel programming to web and data-base subroutines and classes have been made available to the Python programmer. All of this power is available in addition to the mathematical libraries in SciPy.

Head on to this [link](https://www.edureka.co/blog/scipy-tutorial/) for an introduction to SciPy. Another reference for a more comprehensive overview is provided [here](https://www.tutorialspoint.com/scipy/scipy_quick_guide.htm). It includes the implementations of the varied subpackages.

<hr>

## Use of Matplotlib

Matplotlib is one of the most popular Python packages used for data visualization. It is a cross-platform library for making 2D plots from data in arrays. Matplotlib is written in Python and makes use of NumPy, the numerical mathematics extension of Python. It provides an object-oriented API that helps in embedding plots in applications using Python GUI toolkits such as PyQt, WxPythonotTkinter. It can be used in Python and IPython shells, Jupyter notebook and web application servers also.

Matplotlib has a procedural interface named the Pylab, which is designed to resemble MATLAB, a proprietary programming language developed by MathWorks. Matplotlib along with NumPy can be considered as the open source equivalent of MATLAB.

Head on to this [link](https://heartbeat.fritz.ai/introduction-to-matplotlib-data-visualization-in-python-d9143287ae39) for an introduction to data visualisation with matplotlib in python. Another reference for a more quick recap is provided [here](https://towardsdatascience.com/introduction-to-matplotlib-in-python-5f5a9919991f).


