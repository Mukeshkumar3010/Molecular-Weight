# Molecular-Weight
To Calculate Molecular Weight from Periodic Table.

Create a class Element for representing elements in the periodic table
of elements. 
The constructor should deﬁne attributes to store element name, 
atomic number, symbol, and atomic weight, and accessor methods for 
each of these values.
Create appropriate tests to verify the correctness of the implementation
Create a class PeriodicTable. 
The data type should have:
• a constructor that reads values from a ﬁle to create a dictionary whose
keys are strings representing element symbols and whose values 
are Element objects.
The ﬁle elements.txt on moodle contains the data pertaining to elements,
one element per line. 
You will need to loop over the lines of the ﬁle and for each line use 
the string split() method to obtain the ﬁrst four values in it
(name, number, symbol, and weight). 
• a method weight() that takes in a string representing a molecule
name, such as 'H2 O', and returns its molecular weight. 
The string split() method will again be useful here for separating the 
contribution of each atom. 
The methods isdigit() or isalpha() may be used to separate the atomic
symbol (e.g., 'H') from the number of times it occurs
