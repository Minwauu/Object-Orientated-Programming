# Object-Orientated-Programming#

### Quick Fire Five

- **Low cohesion and high coupling - what would make that a bad choice?** - The relationship between the modules would be strong but the sub-programs within each module would be weak and so the high coupling is ineffective.
- **Why should you avoid exception handing to manage the normal or expected flow of control in your program?** It would make the program too complex to understand and difficult to locate where things went wrong. If you know the issue, if/elif/else would be more reasonable. 
- **What is a breakpoint? Can you examine a variables value in the Console window in REPL? Can you change a variable's value? Can you call a function defined in the program?** - https://replit.com/@Minwauu/Breakpoint#main.py 
- **The three combining principles are** Selection, sequence, iteration.

## Objects

Pyhton is an *object-orientated* programming language.

An *object* is a combination of variables (also called *attributes* or *instance variables* or *object variables*) and behaviours (i.e, functions, which are referred to as *methods* in the object context)

To create an object, you need to create a *class* using the keyword *class* as follows: 

![image](https://user-images.githubusercontent.com/110039102/199710382-297ae305-f5bb-4ad6-8ba0-5b6768b8ad7c.png)

https://replit.com/@Minwauu/Object-Orientated-Programming#Class

![image](https://user-images.githubusercontent.com/110039102/200531608-d87ebf0c-2ba2-4b63-81d7-119ef163bc5d.png)

## Inheritance

Inheritance allows a class to be derived from an existing class without the need to modify the existing class. The derived class has all the attributes and methods of the parent class, but adds new ones of its own. Another name fo a derived class is a *subclass*. Inheritance is a type of relationship between classes called an "is-a" relationship.

## Polymorphism:

Giving an action one name, e.g MakeNoise, that is shared up and down an object hierarchy implementing the action in a way appropriate to itself.

![image](https://user-images.githubusercontent.com/110039102/200532575-6b7e331e-274c-46cb-8373-4d71e55ee600.png)

