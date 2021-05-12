What is the difference between forEach, map, filter and reduce ? Explain these using your own words

Ans: foreach and map both are used to ierate through the array
     both receives a function as a parameter
     1.   but the difference is return value
        foreach returns undefined
        map function  retruns a new array with transformed data
    2. as map function returns new array we can attach reduce(), filter() etc
        we cannot do that with foreach as it returns undefined

map method calls the specified function and iterate over all elements of an array for every array element and returns the new array.
     This method doesn't change the original array





Explain the difference between function declaration and arrow function ?

Ans: A function declaration consists of the function keyword, followed by: The name of the function.

Arrow function: are used to write anonymous function expressions in JavaScript
                does not bind its own this, arguments,




Explain the difference between find and findIndex ?

Ans: a. find() method returns the value of the first element in an array that pass a test (provided as a function).

     If it finds an array element where the function returns a true value, find() returns the value of that array element (and does not check the remaining values)
        Otherwise it returns undefine

b. findIndex() method returns the index of the first element in an array that pass a test (provided as a function).
    
    If it finds an array element where the function returns a true value, findIndex() returns the index of that array element (and does not check the remaining values)
        Otherwise it returns -1


If you like to filter out one object element in an array which method do you like to use: filter or find ? Explain
Ans: I would use find(), beacause it will return the object with satisfies the condition
    if we want to filter out more than more than one object element which satisfies conditions then i use filter methodss


Explain the difference of var, let and const when we declare a variable ?

Ans: let:The let statement declares a block scope local variable, optionally initializing it to a value.

         let allows you to declare variables that are limited in scope to the block, statement, or expression on which it is used.

         unlike the var keyword, which defines a variable globally, or locally to an entire function regardless of block scope.

    Var: variable can be declared after it has been used (or) A varible can be
        used before it has been declared.

        This means no matter where functions and variables are declared ,they are moved to the top of their 
        scope regardless of whether their scope is global or local.

    const : Const values are those which can not be changed after declared once.

        The scope of const is block-scoped it means it can not be accessed from outside of block.
        
        JavaScript const variables must be assigned a value when they are declared.
       
        




