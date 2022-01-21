# Introduction to Python

Python is an easy-to-learn and a powerful Object-Oriented Programming language. It is a
very high-level programming language.

Why Python?
1. Easy to Use: Python is comparatively an easier-to-use language as compared to
other programming languages.
2. Expressive Language: The syntax of Python is closer to how you would write
pseudocode. Which makes it capable of expressing the code’s purpose better than
many other languages.
3. Interpreted Language: Python is an interpreted language; this means that the
Python installation interprets and executes the code a line-at-a-time.
4. Python is one of the most popular programming languages to be used in Web
Development owing to the variety of Web Development platforms built over it like
Django, Flask, etc.
Python Download
The very first step towards Python Programming would be to download the tools required
to run the Python language. We will be using Python 3 for the course. You can download
the latest version of Python 3 from https://www.python.org/downloads/
Note:- If you are using Windows OS, then while installing Python make sure that “Add
Python to PATH“ is checked.
Getting an IDE for writing programs:
You can use any IDE of your choice, however, you are recommended to use Jupyter
Notebook. You can download it from https://jupyter.org/install
1
Working in Python
Once you have Python installed on your system, you are ready to work on it. You can work
in Python in two different modes:-
a) Interactive Mode: In this mode, you type one command at a time and Python
executes the same. Python’s interactive interpreter is also called Python Shell.
b) Script Mode: In this mode, we save all our commands in the form of a program file
and later run the entire script. After running the script, the whole program gets
compiled and you’ll see the overall output.
First Program in Python
As we are just getting started with Python, we will start with the most fundamental
program which would involve printing a standard output to the console. The print()
function is a way to print to the standard output. The syntax to use print() function is as
follows:-
In[] : print(<Objects>)
● <Objects> means that it can be one or more comma-separated 'Objects' to be
printed.
● <Objects> must be enclosed within parentheses.
Example: If we want to print “Hello, World!” in our code, we will write it in the following
way:-
In[] : print("Hello, World!")
and, we get the output as:
Out[] : Hello, World!
2
Python executed the first line by calling the print() function. The string value of Hello,
World! was passed to the function.
Note:- The quotes that are on either side of Hello, World! were not printed to the screen
because they are used to tell Python that they contain a string. The quotation marks delineate
where the string begins and ends.
Variables in Python
What are Variables?
A variable in Python represents a named location that refers to value and whose values can
be used and processed during the program run. In other words, variables are labels/names
to which we can assign value and use them as a reference to that value throughout the
code.
Variables are fundamental to programming for two reasons:
● Variables keep values accessible: For example, The result of a time-consuming
operation can be assigned to a variable, so that the operation need not be
performed each time we need the result.
● Variables give values context: For example, The number 56 could mean lots of
different things, such as the number of students in a class, or the average weight of
all students in the class. Assigning the number 56 to a variable with a name like
num_students would make more sense, to distinguish it from another variable
average_weight, which would refer to the average weight of the students. This way
we can have different variables pointing to different values.
How are Values Assigned to A Variable?
Values are assigned to a variable using a special symbol “=”, called the assignment
operator. An operator is a symbol, like = or +, that performs some operation on one or
more values. For example, the + operator takes two numbers, one to the left of the
3
operator and one to the right, and adds them together. Likewise, the “=” operator takes a
value to the right of the operator and assigns it to the name/label/variable on the left of the
operator.
For Example: Now let us create a variable namely Student to hold a student’s name and a
variable Age to hold a student’s age.
