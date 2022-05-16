# Ninja Game 
#Object-Oriented Programming using  Classes, Encapsulation, Abstraction, Polymorphism, and Inheritance.

#Guidelines
this a project called Pirates vs Ninjas, then meet each expectation below in your application. 

Or

As long as you meet each expectation below in your application, you may use any theme you like instead of Pirates and Ninjas. Some examples are, but not limited to.

.

In your main() function Expectations
In your main function, display a cool intro to the game.
Add a game loop into your main() function and give a user an exit choice after the game or a scenario is over.
Using Classes Expectations
Create a class called GameStructure.
For extra credit add a method called RandomRoll to your game which returns a number > 0 and <101.
Using Inheritance Expectations
Create a class called Character which inherits from the GameStructure class.
Create a public property in the Character class and call it Name.
Create 2 classes which inherit from the Character class.  (examples, ninja and pirate). 
Create a method called ThrowStars in the Ninja class which outputs the phrase to the screen "I am throwing stars!";
Create a method called UseSword in the Pirate class which outputs to the screen "I am Swooshing my Sword!".
Create a constructor for both subclasses of the  Character class to initialize all public and private properties in the Character class and subclasses. (Hint: The constructor is only needed in the Ninja and Pirate classes)
Using Encapsulation and Abstraction Expectations
Create one private property called Health in the Character superclass. (Encapsulation)
Create getter and setter public methods in the Character superclass to access and update this private Health property. (Abstraction)
In the setter method check health before setting the value, if the new Health value will be less than zero, then set the property Health to zero and display "Character has Expired..." to the screen.
Using Polymorphism Expectations
Create 2 methods named Talk using Overloading Polymorphism in the Character class.
Give one Talk method this method signature: voidTalk(string stuffToSay)
Give the other Talk this method signature:  void Talk(string name, string stuffToSay)
Make both Talk methods say their name then stuff to say.
Create a virtual attack method in the Character class that returns 10 hit points.
Create an override attack method in both subclasses (Ninja, and Pirate) of the Character class using Overriding Polymorphism and set their attack return values at 25 hit points.
Abstraction Expectations
Create a pure virtual method called Help in the GameStructure class. (Abstraction)
Override the Help method in the Character class.
Override the Help method in both character classes.
