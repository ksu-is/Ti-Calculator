# Ti-Calculator
The idea is to create a scientific Ti-83 with all of the digits to have a better understanding of how it works and how it’s so well programmed to have the capacity to display answers of simple to more complex questions. 
# New Changes 
I added new input to the original code by importing from math and to make sure that the code runs. I am also working on creating new rows to add more features that could be found on the TI-83.
# New Code from tkinter import*
from math import sin as sin
from math import cos as cos
from math import tan as tan
from math import log as log 
# New Code def create_widgets(self):
self.ln_buttn = Button(self, text="ln", width=9, height=3, command=lambda: self.add_chr('ln')) self.ln_buttn.grid(row=5, column=6)
self.log_buttn = Button(self, text="log", width=9, height=3, command=lambda: self.add_chr('log'))
 self.log_buttn.grid(row=4, column=6)
self.sin_buttn = Button(self, text="sin", width=9, height=3, command=lambda: self.add_chr('sin'))
self.sin_buttn.grid(row=1, column=6)
self.cos_buttn = Button(self, text="cos", width=9, height=3, command=lambda: self.add_chr('cos'))
self.cos_buttn.grid(row=2, column=6)
self.tan_buttn = Button(self, text="tan", width=9, height=3, command=lambda: self.add_chr('tan'))
self.tan_buttn.grid(row=3, column=6)

