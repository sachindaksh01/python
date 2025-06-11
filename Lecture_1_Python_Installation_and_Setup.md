Lecture 1: Python Installation and Setup


● Install Python and IDEs (Jupyter Notebook).


● First Python Program: print, comments, and indentation.


Python Installation and IDE Setup


1. Installing Python:


Python is an easy-to-install and widely used programming language. To install Python:


Download Python:


Go to the official.


Download the latest stable version for your operating system (Windows, macOS, or Linux).


During installation, ensure that you check the box "Add Python to PATH" (important for accessing Python via command line).


Verify Installation:


Open a terminal or command prompt.


Type python --version or python3 --version (depending on your OS).


It should display the installed Python version.


2. Installing IDEs for Python Development:


IDEs (Integrated Development Environments) make it easier to write and run Python code. Below are some popular IDEs:


 


Jupyter


Anaconda:


What it is: A distribution that comes with Python and many essential data science packages pre-installed (e.g., NumPy, pandas, matplotlib). It also includes Jupyter Notebook and Jupyter Lab.


Purpose: It's useful if you want a one-stop solution for managing packages, virtual environments, and tools like Jupyter without manually setting up everything.


When to use: If you're doing data science, machine learning, or handling complex dependencies.


Jupyter Notebook:


What it is: A simple interface where you can write and run Python code in a web browser. It's mainly used for interactive coding, data visualization, and sharing results in a readable format.


Purpose: Ideal for experimenting, doing data analysis, and explaining code via markdown.


When to use: When you want a lightweight tool to write and execute code, especially for data science and prototyping.


Jupyter Lab:


What it is: An advanced version of Jupyter Notebook that supports additional features like multiple documents, text editors, and terminals in one interface.


Purpose: It offers more flexibility and supports a broader range of workflows (e.g., working with multiple notebooks, visualizations, and files side by side).


When to use: When you need more functionality, like combining notebooks, terminals, and visualizations in one interface.


Differences between Jupyter Notebook and Jupyter Lab:


● Jupyter Notebook: A simpler interface, mainly for running single notebooks.


● Jupyter Lab: A more advanced, feature-rich environment, supporting multiple panes and documents (like IDEs).


Recommendation:


● Anaconda is useful if you want an easy setup with all tools pre-installed.


● If you're already familiar with Python, you can install Jupyter Lab or Jupyter Notebook separately using pip if you prefer a more minimal setup. Jupyter Lab offers more functionality if you want a more integrated workspace.


 


Jupyter Notebook:


Jupyter Notebook is a popular IDE for Python, especially useful for data science and learning purposes. It allows you to write and execute Python code in cells.


Installation Steps:


● Install pip (Python's package installer) if not already installed. It usually comes with Python.


Open a terminal or command prompt and run the following command:
 bash
 Copy code
 pip install jupyter


To start Jupyter Notebook, type the command:
 bash
 Copy code
 jupyter notebook


● This will open a web-based interface where you can create and manage Python notebooks.


Other Popular Python IDEs:


● PyCharm: Great for professional Python development.


● VS Code: A lightweight editor with Python support.


 


First Python Program: print, comments, and indentation.



 


1. Writing Your First Program:


The simplest Python program consists of printing output to the console. Here's how to do it:


 


# This is a simple Python program


print("Hello, World!")


 


 


● print(): A built-in function used to output text.


● "Hello, World!": The text you want to display in the console.


When you run this code, the output will be:


2. Comments in Python:


Comments are used to explain code and make it easier to understand. Python ignores comments when running the code.


● Single-line comment: Use the # symbol.


● Example:


# This is a single-line comment


print("Hello, World!")


 


 


 


 


 


 


 


● Multi-line comment: You can use triple quotes (''' or """).


● Example:


"""


This is a multi-line comment.


It spans multiple lines.


"""


print("Hello, World!")


 


. Indentation in Python:


Indentation refers to the spaces at the beginning of a code line. In Python, indentation is very important because it defines the scope of loops, functions, and conditionals (instead of using braces {} like other languages).


# This is properly indented


if 5 > 2:


 print("Five is greater than two.")


 


 


Improper indentation will raise an error:


# This will raise an Indentation Error


if 5 > 2:


print("Five is greater than two.")


 


 


 


 


 


 


Practice:


Set 1: Python Installation and Setup


Write a program to display "Hello, World!" on the screen.


Add comments to explain the code you write.


Write a program that prints multiple lines using \n.


Explain what indentation means in Python.


prints a simple triangle using asterisks.


Try running your program without proper indentation. What error do you get?


Comment out parts of your program and observe the output.


Write a multi-line comment explaining what the program does.


 



