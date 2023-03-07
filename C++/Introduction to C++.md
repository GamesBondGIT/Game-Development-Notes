- **Statements**
	- A line of code is called a **statement**. A statement performs a specific task
- **Outputting Text vs Numbers**
	- Text : cout << "Some Text";
	- Num : cout << 22;
- **Program Structure**
	- ![[Pasted image 20230307190153.png]]
	- **`#include<iostream>`**
		- First line of the code adds the **`<iostream>`** header to the program.
		- A header is a file that contains functions and commands.
		- The **`<iostream>`** header in C++ contains the `cout` command.
	- **`using namespace std;`**
		- this tells the program to use the `std` namespace. We need to do this as the `cout` command is part of the `std` namespace.
	- **`int main() {..............}`**
		- Each C++ program has a entry point, or starting point, which is a function called main.
		- Curly brackets indicate the beginning and end of a function. which is also called function body.
	- **`<< endl;`**
		- This adds a new line after the first text. You can use as many `endl` commands as you need.
		- `cout << "This is the first line" << endl; 
		    `cout << "This is the second line";
	- you can use the `<<` symbols to separate different outputs in a single `cout` statement. For example: `cout << "One" << endl << "Two" << endl;`
	- 
- **Variables**
	- A variable lets you store a **value** by assigning it to a **name**. A variable can hold a text value, a number, a decimal, etc.
	- `string message; 
	    `message = "Welcome";
	    `cout << message;`
	    (or)
	    `string message = "Welcome";
	    `cout << message;`
	- `string x = "A";`
	    `x ="B"`
	    `cout << x;`
	    `x ="C";`
	    `cout << x;`
	    output: BC
	- You can declare variables of the **same type** on one line, separated by **commas**.
	    `int x=8, y=2; 
	- The `auto` keyword allows you to set the type of the variable based on its value.
	    `auto x = 4; 
	    `auto y = 3.37; 
	    `auto z = "hello";`
- **Data Types**
	- `int     age    = 29;`
	    `double  temp   = 84.2;`
	    `float   length = 5.31f;`
	    `char x = 'H';`
	    `bool online = false;`
	- `double` is more accurate and more size , `float` is less accurate and less size and compiles quick. The best practice is to use `double`, if you do not have any specific requirements to use `float`
	- in `bool`, false corresponds to 0 and True to 1.
- **Doing Math**
	- `int x = 3; 
	    `int y = 2; 
	    `int z = 1; 
	    `cout << x+y+z+x;`
	    `cout << x-y;`
	    `cout << x/z;`
	    `cout << x%z;`
	    o/p : 9
	- Dividing integers results in an integer. 
	- % (modulo) finds the remainder of a division.