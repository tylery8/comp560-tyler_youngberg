# How to run code:

*Note: All code will automatically terminate in under 30 seconds*

<li>Note: This requires jdk
<li>Open a command prompt and navigate to an appropriate directory
<li> > git clone https://github.com/tylery8/comp560-tyler_youngberg.git
<li> > cd comp560-tyler_youngberg
<li> > cd src
<li> > javac -cp . kenken/*.java
<li> > java -cp . kenken/Main
<li>Paste the input text into the standard input stream or have an "input.txt" file saved in the comp560-tyler_youngberg folder
<p>The standard output will print out the solved puzzle (if solved) and the number of nodes/iterations each method took. If the puzzle is too large, some methods will short-circuit and "exceed 0 nodes/iterations" because they will presumably not be able to solve the puzzle.</p>