###Polymorphism

What does the word 'polymorphism' mean?

- Polymorphism is an objects ability to take on many forms.

What does it mean when we apply polymorphism to OO design? Give a simple Java example.

- In Java we would give an object an ability to be referred to as other types of ojects so it could be grouped together with other objects that share the same functionality or attributes.

What can we use to implement polymorphism in Java?

- We can use interfaces or abstract classes to implement polymorphism in Java.

How many 'forms' can an object take when using polymorphism?

- An object can take just one form at a time, but there is no limit to how many forms it can take, so long as they are all applicable to the object. (It wouldn't make sense to give a radio an interface that gives it the ability to swim... unless maybe that radio is going into a amphibious vehicle and even then... the vehicle will keep it afloat, it shouldn't need to swim.)

Give an example of when you could use polymorphism.

- In Java you could use polymorphism to group together a series of objects that all share a functionality. So - in our homework last night we created amusement parks, they had attractions that could implement security functionality (preventing people who were too short, too young, too old from participating in restricted attractions), and ticketing functionality.  You could group together all the attractions that sell tickets into an Arraylist, and access their shared functionality, or collect them all in an ArrayList made for items that all share security features, and access their security features. In order to access anything outwith that shared functionality - you would need to cast it back to it's original object type or the interface type that holds the functionality you are attempting to access.

###Composition
What do we mean by 'composition' in reference to object-oriented programming?

- Composition refers to what the object HAS, i.e. other objects that may be passed into it, that it can call on for additional functionality.

When would you use composition? Provide a simple example in Java.

- You could use composition to break a larger class down into smaller component classes - to simplify your code and make it easier to work with.  Today we did this by building cars - they have engines or motors, tires, doors, wheels - each of these became children of an abstract superclass called 'components' - this component class held the attributes and methods common to all (for example, double price & getPrice()).

What is/are the advantage(s) of using composition?
- It helps us write drier code - everything that's shared is written once, it is changed in one place if needed, and additional details are added in appropriate sub or child classes.

What happens to the behaviours when the object composed of them is destroyed?

- The components also are destroyed. However, you can not create or destroy energy, just transfer or transform it.  
