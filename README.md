prettyPy
========

This module is used with ipython notebook to write equations and expressions, as a string, in simple math syntax. This program wraps the string in LaTeX to beautify the result. There are two methods of implementation: (I) printing the resulting tag and (II) displaying the equation using the Ipython.display module. <br>

--------------------------------------------------

Example: <br>
from prettyPy import prettyPy as pp <br>
pp.pretty('dy/dx = (y_2 - y_1)/(x_2 - x_1)') <br>
pp.prettyPrint('dy/dx = (y_2 - y_1)/(x_2 - x_1)') <br>

--------------------------------------------------

Developer: Charlie Kawczynski <br>
Email:       charliekawczynski@gmail.com <br>
Available @: https://github.com/charliekawczynski/prettyPy <br>
