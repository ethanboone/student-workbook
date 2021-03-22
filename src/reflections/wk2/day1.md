# Day 1

## Daily Journal
Read Intro to JS > Var, let and const and answer the following questions
1. What is Scope ?
Scope is the area that a variable's value is defined. Variables declared with let or const are block scoped, meaning the scope of that variable is only within the block it's declared in. Var however can either be global or local scoped. If var is used outside of a function, it would be global scoped and can be used anywhere throughout the page. When var is used locally, the value of that variable is only defined within that specific function
2. What is Hoisting ?
The term hoisting refers to variables being declared at the top of the variable's scope. For global variables, they would be declared at the top of the javascript file. Local variables will be before the rest of a functions code block. 
3. In what cases might you use let vs const vs var?
Let would be used in instances the variable may be redefined throughout your program. Const sets a value that cannot be altered throughout the program. Var however, is the previous keyword for declaring a variable before ES6 and is function/local or global scoped opposed to let and const being block scope.