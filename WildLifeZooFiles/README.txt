	The WilfLifeZoo project was created on February 27th 2021. It is a project coded in C++ to demonstrate integration with
Java Programming language. This code reads and writes to a database file of animals. It populates a list of animals
and displays them if the user asks to.
	The project populates a list and displays the list in ascending order by track number well. If given a list that was out
of order on the file, it will be able to display that list in the correct order. It also writes back that list in the correct
order to the file.
	The code is very dependent on the size of each field. If I were to fix the code, I would organize the code much better.
I would rewrite the code to take a file that has different sized fields. It will then populate the animals with the correct
field and in the correct order. I would also use a formatting for the files, like XML.
	This project was extremely challenging to set up. I had to set up the mingw with developer settings so that it can work
with the java programming language. I also orginally created each Animal object with an array of characters. Having an array
of characters lead to a bunch of errors. I switched the array of characters to a string. I found using string is much better
	This program is filled with comments. Those comments should help those who want to maintain or read this code. It also
follows Object Oriented Programming. There is a structure that can help those understand what is going on in the code.