# REGISTRATION-FORM
OUTPUT:

![Screenshot 2024-08-08 105316](https://github.com/user-attachments/assets/fe5af60d-e843-459e-9e12-d6c0a1b534c4)

An ordinary Python library is Tkinter. The quickest and simplest approach to create an object-oriented GUI application is with Python and the tkinter package.
I like to create different GUIs for my Machine learning projects. It gives me freedom of expression to communicate with my end user. Creating a GUI myself for my Machine learning Projects feels like, I am telling the story myself more than anyone else telling my story.

There are many libraries that you can use to build a GUI in Python. Some famous ones are PyQt5, Kivy, PySimpleGUI, Tkinter, etc. I have used Tkinter as it is a simple and basic GUI library that is best for beginners in my opinion. Although there are some limitations to building GUI using Tkinter when it comes to styling your GUI, I use it for quick projects.
 I find it easy to create a GUI using Tkinter and convert it to an executable and distribute it to the end user just by sharing the file. it is quick and economical in terms of time and cost.
You should have Python and Tkinter installed on your system. If you don’t have Tkinter installed, you can install it using pip in Anaconda prompt:

pip install tk

How to start making a simple registration form using Tkinter :

Step 1 : The first step is to import the tkinter module (using either tkinter import * or just import tkinter).

Step 2 : The primary window of the GUI programme was created.

Step 3 : Include one or more widgets in the GUI programme (controls such as buttons, labels, and text boxes, etc.).

Step 4 : Enter the primary events to react to each event that the user has triggered.

Making a registration form using the Tkinter in Python :
This section will discuss the tkinter-based registration form written in Python. At that time, we will talk about widgets and how to use them. The registration page's interface is the only part of the code that is published here. The entire application code is published at the bottom.

So, let's begin by building a simple registration form now, one that requires no backend effort. It can be utilised for database connectivity in the future.

Firstly, we will import the Tkinter module into the Python program.

from tkinter import*  
base = Tk()  
