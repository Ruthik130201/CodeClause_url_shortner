# CodeClause_url_shortner
Module Used :
==> Pyperclip is a cross-platform Python module for copy and paste clipboard functions. It works with both Python 2 and 3. This module was created to enable cross-platform copy-pasting in Python which was earlier absent. The pyperclip module has copy() and paste() functions that can send text to and receive text from your computer’s clipboard. Sending the output of your program to the clipboard will make it easy to paste it on an email, word processor, or some other software.
eg : # importing the library
import pyperclip as pc

number = 100

# copying text to clipboard
pc.copy(number)

# pasting the text from clipboard
text = pc.paste()

print(text)
print(type(text))

output: 100 

==>pyshorteners is a Python lib to help you short and expand urls using the most famous URL Shorteners availables.

With pyshorteners , generate a short url or expand another one is as easy as typing
eg: import pyshorteners

s = pyshorteners.Shortener()
print(s.tinyurl.short('http://www.g1.com.br'))

output: the provided link will short or will get longer as defined as per the code.

==>from tkinter import *
In order to work with a tkinter application, we have to install and import the tkinter library in our environment. Generally, we import the tkinter library in the environment by using from tkinter import * command.
The significance of "import *" represents all the functions and built-in modules in the tkinter library. By importing all the functions and methods, we can use the inbuilt functions or methods in a particular application without importing them implicitly.
eg: In this particular example, we create a functional application that will contain a button and a label widget.

from tkinter import *
from tkinter import ttk
win= Tk()
win.geometry("750x250")
def change_text():
   label.configure(text="Welcome")
label=Label(win, text= "Click the below button to Change this Text", font=('Aerial 20 bold'))
label.pack(pady=30)
button= ttk.Button(win, text="Commit",command=lambda:change_text())
button.pack()
win.mainloop()

output: Executing the above code will display a window that contains a button and a text label showing some text. When we click the button, it will change the message on the screen.
