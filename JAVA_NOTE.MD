# Core Java Interview Questions and Answers
## 1.What is java?
* Java is a simple and most widely used programming language.
* Java is fast,reliable and secure.
* Java developed by James Gosling in 1995 in Sun Microsystem.

## 2.Why are we go for java?
* Java is opensource.
* It is platform independent i.e program written in one operating system is capable of running in all other operating systems due to bytecode concept.
* It runs multiple application at a time.

## 3.What are the main features of java?
**Java has many more features like It is -**
 1. Platform independent
 2. Open source
 3. Multithreading
 4. More secure
 5. Portable
 6. OOPS

## 4.What is platform independent of Java?
* Java is platform-independent because it uses a virtual machine.
* The Java programms are compiled into bytecodes.
* That bytecode can compile on any machine but only if java virtual machine (JVM) is available on a system.
* So java is called platform independent.


## 5.What is mean by Open Source?
*  A program in which source code is available to the general public for use and/or modification from its original design at free of cost is called open source.

## 6.What are IDE/tools availabe in market for java?
* Notepad
* Netbeans
* Eclipse
* JDeveloper(oracle)
* RAD(IBM)

## 7.What are difference between JDK,JVM,JRE?
**JDK:**
* JDK stands for Java Development Kit.
* JDK provides the  environment to develop and run the java application.
* JDK is internally contain JRE + development tools.

**JRE:**
* JRE stands for Java Runtime Environment.
* JRE provides the  environment just to run the java application only.
* JRE internally contains JVM + some Library classes.

**JVM:**
* JVM stands for Java Virtual Machine.
* JVM is an interpreter which is responsible for run the Java program line by line.
* It is mainly used to allocate the memory and compiling.

## 8.What is mean by oops?
* OOPS stands for Object Oriented Programming Structure.
* OOPS is a programming paradigm in which programs are organised as collection of objects, classes and methods.

## 9.What are the coding Standard used in java?
* Pascal notation: Every word's first letter ,must be a capital letter
* Example:GreensTechnology
* Camel notation: First word's first letter should be a small letter, all the other suceeding word's first letter should be a capital letter.
* Example:greensTechnology

## 10.What is mean by class,method,object?
**Class:**
* Class is also called as blueprint/logical entity.
* Class is a collection of objects and it does not contain any space in memory.

**Method:**
* Method defines the set of action to be performed.

**Object:**
* Object is an instance of class that executes the class and it takes spaces like other variables in memory.
* Using object we can call methods.

## 11.What is mean by Encapsulation?
* Binding of data into their corresponding methods as a single unit is called Encapsulation .
* If any java class follows data hiding and abstraction mechanism such type of class is said to be encapsulated class.
* We use encapsulation to make POJO classes.
The main advantages of encapsulation are :
1. We can achieve security.
2. Enhancement will become very easy.
3. It improves maintainability and modularity of the application.
4. It provides flexibility to the user to use system very easily.

## 12.What are the datatypes used in java?
1. byte
2. short
3. int
4. char
5. long
6. float
7. double
8. boolean
9. String

## 13.What is byte size and range of int datatypes?
* Size of byte is 1 byte (8 bit)
* Range formula =[-2^(n-1)] to [(2^(n-1))-1] for int n=32

## 14.What is mean by Wrapper class?
* Wrapper class provides a mechanism to convert primitive data type value into an object and vice-versa. 
> For example - wrapping int into Integer class, wrapping double into Double class, and wrapping char into Character class.
* All wrapper classes default value is null.


## 15.What is the main use of Scanner class?
* To get the inputs from the user dynamically/at the run time.
* It is inside java.util packages.

## 16.What are the methods available in Scanner Class?
1. nextByte();
2. nextShort();
3. nextInt();
4. nextLong();
5. nextFloat();
6. nextDouble();
7. next().charAt(0);
8. next();
9. nextLine();
10. nextBoolean();

## 17.What is mean by inheritance?
* Accessing one class Properties in another class without multiple object creation is called inheritance .
* It avoids time and memory wastage.
* It ensures code re-usability
* Inheritance is 5 types.
	1. Single Inheritance
	2. Multilevel Inheritance
	3. Multiple Inheritance
	4. Heirarchical Inheritance
	5. Hybrid Inheritance
## 18.What are the ways to access the methods /data from another class?
* We can access the another class methods either by creating object or using extends keyword.

## 19.What is mean by polymorphism?
* In Greek word Poly-many,Morphs-form
* Taking more than one forms is called polymorphism or one task implemented in many ways.
* It is two types 
	1. Static polymorphism 
	2. Dynamic polymorphism

## 20.What are the difference between method overloading and overriding?
Method overloading(static binding/compile time polymorphism):
When we have multiple methods with same method name but differs only based on its
datatype, or no. of datatype and order.
* Class-name
* Method-same
* Argument-differ based on datatype,order,number.
Method overriding(dynamic binding/run time polymorphism):
When you are not satisfied with the logic of your super class method,you can create the same
method(with exact same method name) in your sub-class and you can write your required business logic.When you create object for sub-class,sub class method only will get executed.so here child class method overriding parent class method.
* Class name-differ(using extends)
* Method-same
* Argument-same

## 21.What are the types of inheritance?
* Single Inheritance
* Multilevel Inheritance
* Multiple Inheritance
* Hybrid Inheritance
* Hierarchical Inheritance



## 22.Why multiple inheritance is not supported in java?
* Compilation error/syntax error-After extends keyword we can mention only one class name( , not
allowed)
* Priority problem-When multiple parent classes has methods with same name and
arguments,compiler will not know
which method should be called.

## 23.What are the difference between Multiple and Multilevel inheritance?
Multiple inheritance:
* More than one parent class directly supporting into same child class.
* Multiple inheritance not supported in java due to Compilation problem and priority problem
* We have achieve multiple inheritance in java through interface.
Multilevel inheritance:
* More than one parent class supporting into one child class in tree level structure.
* It is supported in java

## 24.What is mean by access specifier?
* It defines the scope or level of access for variables,methods and classes

## 25.What are the difference between public and protected?
### Public:
-------
* It is global level access( same package + different package).
### Protected:
------------
* can access Inside package ( object creation + extends )

## 26.What is mean by Abstraction?
* Hiding the implementation part or business logic is called abstraction.

## 27.What are the types of Abstraction?
* 1. Partially abstraction(using abstract class).
* 2. Fully abstraction(using interface).

## 28.Can we create Object for Abstract class?
* No, we cant create object for abstract class.

## 29.What is mean by Interface?
* Any service requirement specification (SRS) or any contract between 
client and service provider or 100% pure abstract classes is considered as an interface.
* It will support only abstract method(without business logic), won't support non abstract
method(method with business logic)
* In interface "public abstract" is default.
* using "implements" keyword we can implement the interface in a class where we can write the business logic for all unimplemented methods.

## 30.What are the difference between Abstract class and Interface?
Abstract class:
-----------------
* Using Abstract class,we can achieve partial abstraction.
* It support both abstract method and non-abstract method.
* using "extends" keyword you can inherit an abstract class.
* For any abstract method we need to mention "public abstract".
Interface:
-----------
* Using interface,we can achieve full abstraction.
* It supports only abstract method.
* It is using "implements" keyword.
* "public Abstract" is default, no need to mention it explicitly.

## 31.What is mean by String?
* Collection of characters or words enclosed within double quotes is called as String.
* String is a class in java
* String is index based
* Example : "greenstechnology".

## 32.What are the method available in string?
1. equals();
2. equalsignorecase();
3. contains();
4. split();
5. toUpperCase();
6. toLowerCase();
7. subString();
8. isEmpty();
9. identifyHashCode();
10. startsWith();
11. endsWith();
12. CompareTo();
13. charAt();
14. indexOf();
15. lastIndexOf();
16. replace();

## 33.What is mean by constructor?
* Constructor is a special type of method which has no return type, not even void.
* Main purpose of constructor is to perform initialization of an object.
* Before object creation constructor is always called by Compiler.
* If we have not declare any constructor then it will call default constructor automatically.
* If we declare any constructor then it will call default constructor automatically.
* Class name and constructor name must be same.
* It supports method overloading but won't support method overriding.


## 34.Explain the types of constructor?
* Parameterized constructor
* Non parameterized constructor

## 35.Do constructors have any return type?
* No,constructor can't have any return type.

## 36.Write a syntax for creating constructor?
```java
Access-specifier Classname(){
}
```

## 37.What are the rules for defining a constructor?
* Class name and constructor name must be same.
* It should not have any return type.

## 38.Why a return type is not allowed for constructor?
* Constructor is not directly called by your code, its called by memory allocation and object initialization in the run time.
* Its return value is opaque to the user so we cant mention it.

## 39.Can we declare constructor as 'private'?
• Yes,we can declare constructor as private.

## 40.Why a compiler given constructor is called as default constructor?
• If we didn’t create a constructor explicitly it will take the default constructor.

## 41.What is constructor chaining and how can it be achieved in Java?
• The process of calling one constructor from another constructor with respect to current object is
called constructor chaining.
• By using this() and super() methods we can achieve constructor chaining.

## 42.What are the difference between this() and super()?
• this() is used to call class level constructor.
• super() is used to call the parent class constructor.

## 43.What is the super class of all java?
• Object is the super class of all classes in java.

## 44.What are the types of variable?
• Local level variable.
• Global/Class level variable.
• Static variable.
• Final variable

## 45.What is meant by local variable,instance variable,class/static variable?

* Static Variable - It is shared by all the objects in the class.
* Instance variable - A variable declared outside all methods but inside class. We can access this only with
in object.
* Local Variable - A variable declared inside a method/block. We can acces this variable only inside the block.

## 46.What is mean by static keyword in java?
* The static keyword is mainly used for memory management.
* It is used to share the same variable or method by objects of given class.

## 47.Can we override static method in java?
* No, we can't override the static method because it is part of a class rather than an object.

## 48.Can we overload static method in java?
* Yes, we can overload the static method in java.

## 49.What is mean by static variable?
* When a variable is declared as static,then a single copy of variable is created and shared among all object at class level.
* Static variable are essentially global variable.
* All the instance of the class share the same static variable.

## 50.What is mean by static method?
* When a method is declared as static,we need not create object to call the paticular method.We
can call as Classname.methodname()
* Static method in java belong to the class(not to an object).
* They use no instance variables and will usually take the input from the parameters and perform action on it,then return some result.

## 51.What is mean by final keyword and what happens when we declare class,method,variable as final?
* **Final is a access modifier applicable to a variable, method or a class.**
* When a variable is declared as final keyword, its value can't be modified.
* When a method is declared as final we can prevent method overriding.
* When a class is declared as final we can prevent inheritance.

## 52.What is difference between final and finally and finalize()?
**Final:**
* final is a keyword.
* Final variable can't be modified.
* Final method can't be overridden.
* Final class can't be inherited.

**Finally:**
* finally is block associated with try...catch block
* Code given inside finally block will always get executed whether exception occurs or not.

**finalize()**
* finalize() is a method called by JVM before garbage collection

## 53.Where local,static and class variables stores in jvm?
* Static variables are stored in the permGen section of heap memory.
* Local variables are stored in stack.
* Class variables are stored in heap memory.

## 54.What is Exception?
* Exception is an unexpected event which when occurs in a program,your program will terminate
abnormally.
* We can avoid this abnormal termination using exception handling
mechanisms(try,catch,finally,throw,throws)

## 55.Explain about types of Exception?
1. Unchecked exception(Run time exception)
2. Checked exception(Compile time exception)

## 56.What are the difference between checked exception and unchecked exception?
Unchecked exception:
-------------------------
• It will occur at the Run time.
Checked exception:
----------------------
• Checked exception will occur at the Compile time.

## 57.What is the super class for Exception and Error?
* Throwable
* Exception

## 58.Can we have try block without catch block?
• Yes we can have try block without catch block.But in that case finally block must be
present.(There will be no syntax error)
• Possible but we will not able to handle the exception without catch block.

## 59.Can we write multiple catch blocks under single try block?
• Yes,we write multiple catch blocks under single try block.

## 60.How to write user defined exception or custom exception in java?
First customized exception must come under Exception class.
access_specifier method_name() throws customException {
throw new customException();
}

## 61.What are the different ways to print exception message on console?
• ref.printStackTrace() method is used to print the exception message in the console.

## 62.What are the differences between final finally and finalize in java?
Final:
• final is a keyword.
• A final class variable whose value cannot be changed.
• A final method is declared in class level, they cannot be inherited.
• A class declared as final can't be inherited.
Finally:
• It’s a block of statement that definitely executes after the try catch block.
• Exception occurs or not,finally block always get executed.
Finalize:
• It will clean up unused memory space.

## 63.What are the differences between throw and throws?
Throw:
• Throw is a keyword, using which we can throw any any exception.This keyword always given
inside the method.
• At a time we can throw only one exception using throw keyword.
Throws:
• Throws is a keyword, it is used to handle the exception(given in method level).
• we can handle more than one exception using throws keyword.

## 64.Explain Java Exception Hierarchy?
Exception
Unchecked exception(Run time
exception)
Checked exception(Compile
time exception)
ArithmeticException IOException
NullPointerException SQLException
InputMismatchException FileNotFoundException
ArrayIndexOutOfBoundExcepion ClassNotFoundException
StringIndexOutOfBoundExcepion
IndexOutOfBoundExcepion
NumberFormatException

## 65.What is mean by throw and throws?
• Throw is a keyword,used to explicitly throw an exception
• Throws is a keyword, it is used to handle the exceptions(in method level).

## 66.What is mean by array?
• Storing multiple values of similar datatype in a single variable.
• It is index based one.

## 67.What are the advantages and disadvantages of array?
Advantage:
-------------
• In a single variable we can store multiple values.
Disadvantages:
----------------
• It support only similar data types.
• Size fixed at compile time.
• Memory wastage is high.

68.Different ways to intialise array?
• Datatype refName[]= new Datatype[size];
• Datatype[] refname={ value1,value2,....};

69.Can we change the memory size of array after initialization?
• No,we can't change the memory size of array after initialization.

70.What is collection ?
• It will support storage of multiple values with dissimilar data types.
• It is dynamic memory allocation.
• No memory wastage like array.

## 71.What is the difference between ArrayList and Vector?
ArrayList:
----------
• Asynchronized
• It is not a thread safe
Vector:
-------
• Synchronized
• Thread safe

## 72.What is the difference between ArrayList and LinkedList?
LinkedList:
-----------
• Insertion and deletion is a best one.
• Searching/retrieving is a worst.
• It’s makes performance issue.
ArrayList:
----------
• In Arraylist retrieve/searching is a best one
• In ArrayList deletion and insertion is a worst one because if we delete/insert one index value after
all the index move to forward/backward.
• It makes performance issue.

## 73.Difference between Collection and Collections
• Collection-Collection is an interface under which we have list,set,queue
• Collections-is an utility class in which we have lots of predefined methods which we can apply
over collection objects.
E.g : Collections.min(),Collections.max(),Collections.sort()

## 74.Describe the Collections type hierarchy ? What are the main interfaces ?
Collection:
------------
• List
• Set
Map----doesnt come under collection,it is a separate interface in java
Hierarchy:
-----------
List:
----
• ArrayList
• LinkedList
• Vector
Set:
----
• Hashset
• LinkedHashSet
• Treeset
Map:
----
• HashMap
• LinkedHashMap
• Hashtable
• TreeMap
• ConcurrentHahMap

## 75.What is difference between set and List?
Set:
----
• It is a value based one.
• It prints in random order.
• It won't allow duplicates.
List:
-----
• It is a Index based one.
• It prints in insertion order.
• It allow duplicates.

## 76.What is the difference between HashSet and TreeSet ?
HashSet:
---------
• It prints in random order.
TreeSet:
---------
• Treeset prints in ascending order


## 77.How to convert List into Set?
• By addAll() we can convert List into set.(all the elements in list will get added to set)

## 78.What is map?
• It is key and value pair.
• Here key+value is one entry.
• Key ignore the duplicate value and value allow the duplicates.

## 79.What is difference between Hash Map and Hash Table?
HashMap:
• Key allows single null.
• Asynchronised(not thread safe).
Hashtable:
• Key and value won't allow null.
• Synchronised(thread safe).

## 80.What is difference between set and Map?
Set:
• It is a value based one.
• It print in random order.
• It won't allow duplicates.
Map:
• It is key and value pair.
• Here key+value is one entry.
• Key ignore the duplicate value and value allow the duplicates.

## 81.Can we iterator the list using normal for loop?
• Yes,we can iterate the list using both normal and enhanced for loop.

## 82.What are the methods available in list But not in set?
• indexOf();
• get();
• lastIndexOf();

## 83.Explain about user defined Map?
• It is key and value pair.
• Here key+value is one entry.
• Key ignore the duplicate value and value allow the duplicates.

## 84.How much null allows in below maps:
• HashMap :k?,v?
• LinkedHashMap:k?,v?
• TreeMap :k?,v?
• HashTable :k?,v?
• HashMap :k-1 null,v- n null
• LinkedHashMap:k-1 null,v- n null
• TreeMap :k-ignore null,v- allow null
• HashTable :k-ignore null,v- ignore null

## 85.How to Iterate Map?
• We can iterate the map by using entrySet() method.

## 86.What is the return type of entrySet?
• Set<Entry<key,value>>

## 87.Write the methods to get the key only and value only?
• For key only keySet() method is used.
• For value only values() method is used.

## 88.What is mean by File? In which package it is available?
• File is a class and it is used to achieve the file operation.
• It is available in java.io package.

## 89.What are the methods available in File ?
• mkdir();
• mkdirs();
• list();
• createNewFile();
• isDirectory();
• isFile();
• isHidden();

## 90.While creating a file if we not mention the format then under which format it will save the file?
• If we do not mention the file format it will automatically take format as file.

## 91.What are the difference between append and updating the file?
For updating the file:
It will replace the old contents of the file.
For appending the file:
It will add the contents at the end of the file.

## 92.What is mean by Enumerator,Iterator and List Iterator?
Enumeration:
• It is an interface used to iterate only legacy class or interface.
• Only iterates in forward direction
Iterator:
• It is an interface used to iterate the collection objects
• Only iterates in forward direction
List Iterator:
• It is an interface used for iterating list type classes
• iterates in forward as well as backward direction

## 93.Difference between Enumurator,Iterator and List Iterator?
Enumerator:
• applicable only for legacy class and interface
• no remove method is available.
• no Backward direction is possible
Iterator:
• It is an Interface used to iterate the collection objects
• remove method is available.
• no Backward direction is possible.
ListIterator:
• It is an interface used for iterating list type classes
• remove method is available.
• Backward direction is possible.

## 94.What are the methods available in Enumerator,Iteratorand List Iterator?
Enumerator Methods:
• hasMoreElements();
• nextElement();
Iterator Methods:
• hasNext();
• next();
• remove();
ListIterator Methods:
• hasNext();
• next();
• remove();
• hasPrevious();
• previous();

## 95.Explain JDBC connection steps?
• Import JDBC packages.
• Load and register the JDBC driver.
• Open a connection to the database.
• Create a statement object to perform a query.
• Execute the statement object and return a query resultset.
• Process the resultset.
• Close the resultset and statement objects.
• Close the connection.

96.What are control statement?
• Statement which has control over the loop or program is called control statements.
• Example:if,if else,for,while,dowhile etc

## 97.Different control statements available in java
Break:
------
• It is used to terminate the loop
Continue:
----------
• It is used to skip the current iteration.
while and do while
----------
While:
------
• It is entry check loop.
Do While:
---------
• It is a exit check loop.
if and if else
===============
if
• executes only when the condition becomes true.
if else
• executes the else part when the condition becomes false and executes if part when condition
becomes true.

## 98.Difference between immutable and mutable string
immutable and mutable string
==============================
Immutable string:
• Once created,we cant change the value in memory
• In concatenation, it will create new memory
mutable string:
• After creation,we can modify the value in reference(memory)
• In concatenation, its takes same memory

## 99.Difference between Remove all() and Retain all

removeAll():
• removeAll() is a method , it is used to compare the 2 lists and remove all the common values
retainAll():
• retainAll() is a method, it is used to compare both lists and retains only the common values

## 100.Difference between Literal String and Non literal string

**Literal String:**
* In case of String duplicates,it will share the same memory address
* Its stored inside the heap memory(string pool or string constant).
* It share the memory if same value (duplicate value)

**Non literal string:**
* Even in case of String duplicates,it will have different memory address.
* It’s stored in the heap memory.
* Its create a new memory every time even if it is a duplicate value(same value)


## 101.Difference between Heap and stack memory
**Heap memory:**
* Heap is used for dynamic memory allocation.
* Memory access is slow.

**Stack memory:**
* Stack is used for static memory allocation.
* Variables allocated on the stack are stored directly to the memory and access will be very fast.

## 102.What is the default Package in java?
• java.lang

## 103.What are the difference between equals() & hashcode()?
equals:
• Used to compare the two string.
Hashcode:
• Used to return the address where it stored.

## 104.How can we make Array list As a synchronized?
• collections.SynchronisedList(refName of array);