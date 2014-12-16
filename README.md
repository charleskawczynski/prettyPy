prettyPy
========

This python module can be used with ipython notebook to write equations and expressions, as a string, in simple math syntax. This program wraps the string in LaTeX to beautify the result. There are two methods of implementation: (I) printing the resulting tag and (II) displaying the equation using the Ipython.display module. I look forward to integrating this module with LaTeX as well. <br>

--------------------------------------------------

Example:
```Python
from prettyPy import prettyPy as pp
pp.pretty('dy/dx = (y_2 - y_1)/(x_2 - x_1)')
pp.prettyPrint('dy/dx = (y_2 - y_1)/(x_2 - x_1)')
```
--------------------------------------------------

Developer: Charlie Kawczynski <br>
Email:       charliekawczynski@gmail.com <br>
Available @: https://github.com/charliekawczynski/prettyPy <br>
