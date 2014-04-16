prettyPy
========

This program receives a string of some equation and wraps it in LaTeX code, and outputs the result to reduce the verbose implementation of writing LaTeX equations.

Example:
from prettyPy import prettyPy as pp <br>
a = 'b*cos(theta) + c**(d*sin(gamma))' <br>
pp.prettyPrint(a) <br>
print pp.pretty(a) + ' = ' + str(eval(a))


Developer: Charlie Kawczynski

Email:       charliekawczynski@gmail.com

Available @: https://github.com/charliekawczynski/prettyPy
