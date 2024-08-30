## Can you run a code even before main method is invoked ?
- Yes, in Java, you can run code even before the main method is invoked. This is achieved through the use of static blocks. Static blocks are executed when the class 
is loaded into memory, and before the main method is executed.
- A static block in Java is a block of code that is defined using the static keyword. It’s used for initializing static variables or for performing any setup that
  needs to be done before the class is used.
- They are executed only once when the class is loaded.

## can we use 'this' and 'super' keyword together ?
- No in case of constructor, yes in case of method.
- this and super can be used together in the same method or constructor, but there are some restrictions:
- In Constructors:
You cannot use this() and super() together in the same constructor. This is because both this() and super() must be the first statement in a constructor,
and you can only have one first statement.
- In Methods:
You can use this and super in the same method to access members of the current class and the superclass, respectively. For example, you might use this to refer
to a field in the current class and super to call a method from the superclass.

## What is the diff btw System.out, System.err and System.in ?
- System.out, System.err is used to print output on console. System.err.println prints only error message.
- System.in is used to read input from the console often used with Scanner class.
  Scanner scanner = new Scanner(System.in);

## Tell me about final, finally, finalize ?
- final is a keyword, finally is a block and finalize is a method.
- final keyword is used to apply restrictions on variable, method and class. A final variable cannot be reassigned, a final method cannot be cannot be overridden by 
  subclasses and final class cannot be extended. ex: If you dont your test classes to be extended further, declare it final.
- finally block is used in exception handling. It is a block that follows a try-catch structure and is used to execute important code such as closing resources, 
  regardless of whether an exception is thrown or not. The finally block is always executed, even if an exception occurs.
- A method used to perform cleanup before an object is garbage collected.

## what is the order of call of constructors in inheritance ?
- In case of inheritance when object of child class is created, then parent class contructor is invoked first and then child class contructor.

## explain method overloading ?
Method overloading in Java is a feature that allows a class to have more than one method with the same name, as long as their parameter lists (i.e., the type, number, or order of parameters) are different. Method overloading is determined at compile time (also known as compile-time polymorphism or static polymorphism).
This means that the method to be invoked is determined at compile time, based on the method signature and the arguments provided. 
The decision about which overloaded method to invoke is made during the compilation process, not at runtime.

## can we overload static methods ?
Yes, if the methods have diff input parameters it can be overloaded.
but if there are no input parameters or if the number of parameters and types of parameters is the same and method differ only by static key word then we cannot overload it.









  
  


