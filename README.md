# Lesson08

For reading:
1)https://www.geeksforgeeks.org/c-sharp-interface/                                                                                                               
2)https://www.tutorialsteacher.com/csharp/csharp-struct                                                                                                             
3)https://www.geeksforgeeks.org/c-sharp-abstract-classes/																										
4)https://www.c-sharpcorner.com/uploadfile/prasoonk/abstract-class-vs-interface/																					
5)https://www.tutorialspoint.com/json/index.htm (Finish all articles in JSON basic tutorial )																		
6)https://www.tutorialspoint.com/csharp/csharp_encapsulation.htm																								
7)https://www.c-sharpcorner.com/article/encapsulation-in-C-Sharp/																									
8)https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/object-oriented/polymorphism																			

Taks:
1) Create a C# program that implements an IVehicle interface with two methods, one for Drive of type void and another for Refuel of type bool that has a parameter of type integer with the amount of gasoline to refuel. \ Then create a Car class with a builder that receives a parameter with the car's starting gasoline amount and implements the Drive and Refuel methods of the IVehicle.
The Drive method will print on the screen that the car is Driving, if the gasoline is greater than 0. The Refuel method will increase the gasoline of the car and return true. To carry out the tests, create an object of type Car with 0 of gasoline in the Main of the program and ask the user for an amount of gasoline to refuel, finally execute the Drive method of the car.
Input
50
Output
Driving

2)Create a C# program that prompts the user for three names of people and stores them in an array of Person-type objects. There will be two people of the Student type and one person of the Teacher type.

To do this, create a Person class that has a Name property of type string, a constructor that receives the name as a parameter and overrides the ToString () method.

Then create two more classes that inherit from the Person class, they will be called Student and Teacher. The Student class has a Study method that writes by console that the student is studying. The Teacher class will have an Explain method that writes to the console that the teacher is explaining. Remember to also create two constructors on the child classes that call the parent constructor of the Person class.

End the program by reading the people (the teacher and the students) and execute the Explain and Study methods.

Input
Juan
Sara
Carlos

Output
Explain
Study
Study

3)Create a C# program that implements an abstract class Animal that has a Name property of type text and three methods SetName (string name), GetName and Eat. The Eat method will be an abstract method of type void.

You will also need to create a Dog class that implements the above Animal class and the Eat method that says the dog is Eating.

To test the program ask the user for a dog name and create a new Dog type object from the Main of the program, give the Dog object a name, and then execute the GetName and Eat methods.

Input:
Tobby


Output:
Tobby
Eating

4)Create a C# program that prompts the user for three names of people and stores them in an array of Person-type objects. To do this, first create a Person class that has a Name property of type string, a constructor that receives the name as a parameter, a destructor that assigns the name to empty and overwrites the ToString () method.

End the program by reading the people and executing the ToString () method on screen.

Input
Juan
Sara
Carlos

Output
Hello! My name is Juan
Hello! My name is Sara
Hello! My name is Carlos
