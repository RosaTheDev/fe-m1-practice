1.  How do you declare a variable. What does the equals sign really mean in JavaScript? What is it called in JavaScript?
- You can decalre a variable by using var, the equal sign in JavaScript is the assignment operatior.

2.  There are three big data types in JavaScript: numbers, strings, and booleans. Describe what each of them are.
- Numbers: Arithmetic operators used for calculating sums. 
- Strings: Are enclosed in a pair of quotes, either with double quotes or single quotes and must have a closing quotes
-Booleans: Logical operators, in two values either 'true' or 'false'

3.  What are the six rules for naming variables? What are a few JavaScript reserved words that you should avoid using for variable names?
  1: The name must begin with a letter, dollarsign, or an underscore, it must NOT start with a number.
  2: The name can contain letters, numbers, dollar sign, or an underscore. Note you must not use a dash or a period in the variable name.
  3: You cannot use keywords or reserved words. Keywords are special words that tell the interpreter to do something. i.e. var 
  4: All variables are case sensative, so 'score' and 'Score' would be different variable names, but it is bad practice to create two variables that have the same name using different cases. 
  5: Use a name that describes a kind of inforamtion that the variable stores. i.e firstName can hold a person's first name
  6: If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word. i.e. firstName rather than firstname **This is called CamelCase**

4.  How can an array be useful when dealing with multiple related values? How do you access/change a value in an array?
- If you do not know how much a list will contain, consider using a variable instsead, this way instead of having a bunch of variables with first names, an array could save that space. you can access or change the value in array by referncing its index such as [0],[1],[2]
5.  What is the difference between an expression and a statement?
- A statement is direct such as declaring a variable i.e. firstName = "Alfred"
- An expression requires it to do more work such as finding sums i.e. sum = 2 + 2

6.  What are three types of operators and how are they used?
- Assignment operator: can be used to set a boolean, string, number ect to a variable otherwise known as the equals sign i.e sum = 2 + 2
- Artihmeic operator: can be  * to multiply, / to divide. Used to do mathmetical operations
- String operator: are quotations when you see quotations in code it usually means that is a sting, it could be single or double quotations.
- Comparison operator: are usually less than or greater than signs used to return a true or false value 
- Logical Operators: are &&, ||, ===, ==, which are used to compine expressions and also to return a true or false