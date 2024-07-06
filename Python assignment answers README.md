[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15378394&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   Python is an open-source programming language that is free to use and distribute. Some of its key features are
   a. open source language.
   b. large standard library.
   c. Platform independent
   d. Large community support.
   e. Object oriented.
   f. Dynamically typed.
   g. High level Language.
   h. Extensible and embeddable.


   Examples of use cases where python is particularly effective are statistical analysis were Python helps conduct complicated statistical calculations so you can save more time and hassles manipulating and analyzing them.

   However python is used in website development and software development Whether you need to connect the front end and back end of a website, send information to and from servers, store data, or deal with databases, Python is the answer to all your woes. It has a wide variety of website and software development frameworks, including Django and Flask, to fit your needs.


2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   **HOW TO INSTALL PYTHON ON WINDOWS**
   a. Go to the official Python website's Windows downloads page and download one of the Stable Releases of Python.

   b. download the Windows Installer (64-bit) for modern hardware. Once the download is complete, double click the installer to launch it.

   c.You'll see the installer welcome screen which describes what the installer will do. Make sure that Add python.exe to PATH is checked in the installer. This makes it easier to use Python from the command prompt -- you just need to enter "python" to start, rather than the full path to the executable.

   d. When you are ready to being the installation you can click Install Now.

   e. The install will proceed as normal, installing all the required libraries (including Tcl/Tk for Tkinter). Once complete you can exit the installer.

   f. Open a command prompt and start python by entering python. This will start the Python REPL, where you can enter interactive Python code.
   
   g. Create the virtual environment in a desired directory using the following command "python -m venv env"

   h. The above command  will create a new folder called env inside the directory where you executed the command. You can activate the created virtual environment by running the following command in the same directory where you executed the last command "cd env/Scripts && activate && cd ../../"


3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   # python program to print "Hello World" 
print("Hello World")

**OUTPUT**
Hello World

The Python syntax defines a set of rules that are used to create a Python Program. The basics syntax elements used in the program are
1. **Values**
Use quotation marks (" or ') around a string
Use decimal points (.) to turn an int into a float
Booleans can only be True or False

2. **Functions**
Use parentheses (()) after the name to use a function
Add the parameter between the parentheses if needed (like in print)

3.**Comments**
Use an octothorpe (#) to start a single-line comment
Use triple quotes (""") around a multi-line comment
Some common operators
A = B
Set variable A to the value of B
A + B
Add A and B
A - B
Subtract B from A
A * B
Multiply A by B
A / B
Divide A by B

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

a. **Numeric**:-The numeric data type in Python represents the data that has a numeric value.A numeric value can be an integer, a floating number, or even a complex number

-Integers – This value is represented by int class. It contains positive or negative whole numbers (without fractions or decimals). In Python, there is no limit to how long an integer value can be.

-Float – This value is represented by the float class. It is a real number with a floating-point representation. It is specified by a decimal point. Optionally, the character e or E followed by a positive or negative integer may be appended to specify scientific notation.

-Complex Numbers – A complex number is represented by a complex class. It is specified as (real part) + (imaginary part)j. For example – 2+3j

b. Sequence Type:- These are collections of data types that can be the same or different. Examples include list, string, and tuples.

c. Boolean:- Python Data type with one of the two built-in values, True or False. Boolean objects that are equal to True are truthy (true), and those equal to False are falsy (false). However non-Boolean objects can be evaluated in a Boolean context as well and determined to be true or false.

d. Set:- Set is an unordered collection of unique items. Set is defined by values separated by commas inside braces

e. Dictionary:- A dictionary in Python is an unordered collection of data values, used to store data values like a map, unlike other Python Data Types that hold only a single value as an element, a Dictionary holds a key: value pair. Key-value is provided in the dictionary to make it more optimized.



5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   Loops and conditional statements are powerful constructs that allow programmers to automate repetitive tasks and control the flow of their programs based on certain conditions. Python provides two basic types of loops to iterate through objects or functions: the for and the while loop statements. Both loop types have additional options and can be combined with conditional statements.

   **Example of IF-ELSE statement**
   variable_2_test = "ice cream"
if "cream" in variable_2_test:
	print("It's creamy, for sure.")
elif "ice" in variable_2_test:
    print("It's cold, ice-cold cream.")
else:
	print("Anything but ice cream.")
   It's creamy, for sure.

   **Example of FOR statement**
   for e in range(0,8,2):
	print("e is %d now." % e)

flavors = ["chocolate", "bread", "cherry"] 
for index in range(len(flavors)): 
    print(flavors[index])
else:
    print(" --- end of first loop.")
    
# produces the same
for e in flavors:
    print(e)

    e is 0 now.
e is 2 now.
e is 4 now.
e is 6 now.
chocolate
bread
cherry
 --- end of first loop.
chocolate
bread
cherry.

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

-->We use functions in programming to bundle a set of instructions that you want to use repeatedly or that, because of their complexity, are better self-contained in a sub-program and called when needed. That means that a function is a piece of code written to carry out a specified task. 

There are three types of functions in Python:

Built-in functions, such as help() to ask for help, min() to get the minimum value, print() to print an object to the terminal

Example is def add_two_num(a,b):
    sum=a+b;
    return sum; 
    
num1=int(input("Input the first number : "))
num2=int(input("Input the second number  :"))

print("The sum of given two numbers is",add_two_num(num1,num2))
   **OUTPUT**
   def add_two_num(a,b):
    sum=a+b;
    return sum; 
num1=int(input("Input the first number : "))
num2=int(input("Input the second number  :"))
print("The sum of given two numbers is",add_two_num(num1,num2))



7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

   **LIST**                                              **DICTIONARIES**
1.An ordered collection of items          1.An unordered collection of data in a key: value pair form.
2.Uses square brackets []                 2.Uses curly braces {}
3.Accessed by index, starting from 0      3. Values are accessed using keys.
4.Allows duplicate items.                 4.Does not allow duplicate keys
5.Faster for ordered operations like sorting. 5.Faster for lookup operations due to the hash mapping of 
                                                   keys.

A script that creates a list of numbers and a dictionary  is                                                   

Input : test_list = [{‘gfg’ : 1, ‘is’ : 4, ‘best’ : 6},

             {‘gfg’ : 10, ‘is’ : 3, ‘best’ : 7},

             {‘gfg’ : 9, ‘is’ : 4, ‘best’ : 2},

             {‘gfg’ : 4, ‘is’ : 1, ‘best’ : 0},

             {‘gfg’ : 6, ‘is’ : 3, ‘best’ : 8}], key, value = ‘gfg’, ‘best’

Output : {1: 6, 10: 7, 9: 2, 4: 0, 6: 8}

Explanation : Dictionary with ‘gfg”s keys and ‘best”s values is constructed.

Input : test_list = [{‘gfg’ : 1, ‘is’ : 4, ‘best’ : 6},

             {‘gfg’ : 10, ‘is’ : 3, ‘best’ : 7},

             {‘gfg’ : 9, ‘is’ : 4, ‘best’ : 2}], key, value = ‘gfg’, ‘best’

Output : {1: 6, 10: 7, 9: 2}

Explanation : Dictionary with ‘gfg”s keys and ‘best”s values is constructed.


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

 ---> Exception handling in Python is a process of resolving errors that occur in a program. This involves catching exceptions, understanding what caused them, and then responding accordingly.

   **Example of try exceptional handling**
   try:
x = 5 / 0
except ZeroDivisionError:
print("You can't divide by zero!")

**Example of except as exceptional handling**
try:
  x = 1/0
except ZeroDivisionError:
  print("Division by zero not allowed")
finally:
  try:
    print(y)
  except NameError:
    print("Variable y is not defined")


   **Example of finally**
   try:
  x = 5
  y = 0
  z = x/y
except ZeroDivisionError:
  print("Error: Cannot divide by zero")
finally:
  print("All done")



9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

    **a module**- is a single file containing Python definitions and statements. These definitions and statements can include variables, functions, and classes and can be used to organize related functionality into a single, reusable package. Module organizes and reuses code in Python by grouping related code into a single file.

    **Python Packages**- are collections of modules that provide a set of related functionalities, and these modules are organized in a directory hierarchy. In simple terms, packages in Python are a way of organizing related modules in a single namespace.

    How to import module in my python script
   is by You all must be familiar with pi. The pi is depicted as either 22/7 or 3.14. math.pi provides a more precise value for the pi.

    example import math 
    print (math.pi)

   **OUTPUT**
   3.141592653589793



10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

    In Python, there are six methods or access modes, which are:
    1.Read Only ('r’)
    2.Read and Write ('r+’)
    3.Write Only ('w’):
    4.Write and Read ('w+’)
    5.Append Only ('a’):
    6.Append and Read (‘a+’):

    **HOW DO TO READ FROM AND WRITE TO FILES IN PYTHON**
    1.The read() method:
    Eg is
     f = open("myfiles.txt", "r")
#('r’) opens the text files for reading only
print(f.read())
#The "f.read" prints out the data in the text file in the shell when run.

    2.The readline() method
    Eg is
    f = open("myfiles.txt", "r")
print(f.readline()

     
   **A script that reads the context of a file and prints it to the console**
   "File_object.read([n])" OR  "File_object.readline([n])"

   **A script that writes a list of string to a file**
   "File_object.write(str1)" OR  "File_object.writelines(L) for L = [str1, str2, str3]"

   **REFERENCES**
   1. https://www.geeksforgeeks.org/reading-writing-text-files-python/
   2. https://www.shiksha.com/online-courses/articles/difference-between-module-and-package-in-python/#:~:text=In%20Python%2C%20both%20modules%20and,explore%20the%20differences%20between%20them.
   3. https://www.datacamp.com/tutorial/modules-in-python
   4. https://www.almabetter.com/bytes/tutorials/python/exception-handling
   5. https://copyassignment.com/python-a-function-that-accepts-2-integers-and-adds-them-and-returns-their-sum/


# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


