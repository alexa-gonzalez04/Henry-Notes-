# Henry notes
## Variables 

**var** 
This variable can change.

    var nameofvar = "content of the variable";

**const**
This is a CONSTANT variable, it´s mean what5 the value can´t change.

    const pi = "3,14"

**let**

## Functions
Take code and save in the memory. Basicly are used for don´t replay the same code again, the function do something.
 

**Function syntax**

Fist we start with the keyword "function", second we put a name of the function (use describe what they do), then we add two parentesis and two keys. Inside of de keys is where we put the code to execute. AFTER an any line of code we ALWAYS put an ";" is a good practice.

*function*

    function nameofuction() {
        **code
    }

To call this invoke:

    nameofunction();

*var + function*

For call this function we use the name of the variable, cause the function is inside.

    const nameoffunction = function () {
        **code
    }


**print**

    console.log("argument"))

Example:

1. We have a function what introduce your self, we have an simply structure.

    function introduce() {
    console.log("Hi! I am Alexa");
     console.log("I got 18 years old");
    }

2. Add the arguments, in this case are "name" and "age".The fuctions don´t gonna work cause the args ARE UNDEFINED YET.
 
    function introduce(name, age) {
    console.log("Hi! I am" +name);
    console.log("I got 18 years" +age);
    }

3. Define the arguments (they work like variables). Use the name of the function, parentesis with the parameters inside and finally semicolon.

    introduce(" Alexa", " 18");

Output

Hi! I am Alexa
I got 18 years 18

**Arguments**

    function nameofuction(arguments) {
        **code
    }

**Scope** is like a line of code that can be interpreted or not, it´s depends of the context.

Example:

1. 
 
 - Here we have an simple function, wich returns "Bye + username". In this case I defined the argument/variable with the parameter "Abigail". 

         function sayBye(name2) {
        console.log("Bye" +name2);
        }
        undefined

        sayBye("Abigail");
        Bye Abigail 
        
- Here we can see wich the variable "name2" is just defined INSIDE of the function, and not in the global code.

        name2
        { name2 is not defined }




2.
- Contary to example 1, in this case the var has value in the global code.

        var name = "Alexa"
        undefined

        function sayHi(){
        console.log("Hi, my name is " +name);
        }
        undefined
    
        sayHi();
        Hi, my name is Alexa

**Return** all functions return for defaul, sometimes that can be "Undefined".

Example:

    function return() {
        return 15;
    }  

 output: 15

    function add(a, b) {
        return (a + b);
    }
    undefined
    add(1, 2)
    3
    
    add(1, 1) + add(2, 2)
    6
    function subs(x, y) {
    return (x - y)
    }
    undefined
    subs(10, 8)
    2
    add(5, 5) + subs(10 , 8)
    12

**Flow control** it a way in wich we can check if something is true or false.

Example:

    function canDrive(age) {
    if (age > 18) {
    return true;
    }
    return false; 
    }
    undefined
    canDrive(67);
    true

    canDrive(15)
    false