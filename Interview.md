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

## 
  


