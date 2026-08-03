Python Basics List:
 What is a list, and when would you use one in Python?- A list in python terms is a built-in, mutable, and ordered collection of items enclosed in sqaure brackets
Tuple: How is a tuple different from a list?- lists are mutable while tuplets are immunatable
Set: What makes a set different from a list?- a set is an unordered collection of unique, hashable items while a list is ordered.
Mutable: What does it mean if an object is mutable?- a mutable object is one of whose internal state, valie, or data can be modified or changed after it has been created without changing its unique memory adress or identify.
Immutable: What does it mean if an object is immutable?- an item whose internal state or content cannot be modified after it is created.

Functions & Dictionary Methods len(): What does the len() function return?- it returns the numbers of items (length) in an object like a list, string, or dictionary.
.get(): Why would you use the .get() method with a dictionary?- it retreives a value without raising a keyerror if the key does not exist. it returns none or a specified default instead.
.length(): Is .length() a valid Python method? If not, what should you use instead?-  No, it aint vaild. you have to use he built-in function instead.
.keys(): What information does the .keys() method return?-  it returns a view object containing all the keys present in the dictionary.
.values(): What information does the .values() method return?- it returns a view view object containing all the values present in the dictionary.

List Methods
.remove(): What does the .remove() method do to a list?- it removes the first occurrence of a specific value from the list.
.pop(): How is .pop() different from .remove()?- .pop() removes and returns an item by its index (defaulting to the last item), while .remove() deletes an item by its value.
.sort(): What happens when you use .sort() on a list?- it sorts the items of the list in plqce (usaully in ascending order) and modifies the originak list.
.append(): What does the .append() method do?- it adds a single item to the very end of the list.
.insert(): How is .insert() different from .append()?-  .insert() adds an item at a specific index position, whereas, .append() always adds it to the end.

Object-Oriented Programming (OOP) Class: What is a class in Python?- a blueprint of template used to create objects, defining their common attributes and behaviors
Object: What is an object, and how is it related to a class?- an instance of a class containing actual data. the class acts as the blueprint, and the object is the built structure
Abstraction: What is abstraction, and why is it useful?- hiding complex internal implemenation details and showig only essential features. it reduces complexity for the user.
Encapsulation: How does encapsulation help protect an object's data?- it restricts direct access to methods and variables by wrapping data and code together , often using private variables to prevent  unintended changes.
Inheritance: What is inheritance, and why is it useful? Polymorphism: How can different classes use the same method name but produce different results?- polymorphism allows different classes to define their own specific version of a method with the exact same time and inheritiance- allowas a new class to adopt attributes and methods from an exisiting class, promoting code reuse
constructor: What is a constructor (init()), and when is it automatically called?- a special method used to initialize an objects attributes. it is automatically called when a new object of that class is made.

Challenge Questions Which Python collection type cannot be changed after it is created?- tuple
 Which collection automatically removes duplicate values?- set
What is the difference between a list and a dictionary?- list
Which list method would you use to add an item to the end of a list?- append()
Which dictionary method would you use to safely retrieve a value by its key?- get()
What is the difference between a class and an object?- inheritcance lets a child class inherit methods from a parents class, while polymorphism allows a child to override or change how those inherited methods behave.
 How do inheritance and polymorphism work together in object-oriented programming?- they automatically initialize an objects attributes and set up its starting state when the object is created.
  Why are constructors important when creating objects?- a constructor is a special method in a class that automatically  runs when a new object is instantiated to initialize its values.