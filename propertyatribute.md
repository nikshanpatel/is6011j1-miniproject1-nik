7. **Property/Attributes**

Attributes are created inside of a class definition. We can dynamically create arbitrary new attributes for existing instances of a class. We do this by joining an arbitrary name to the instance name, separated by a dot ".". 
The instances possess dictionaries __dict__, which they use to store their attributes and their corresponding values.
Attributes can be bound to class names as well. In this case, each instance will possess this name as well. 

Properties are special kind of attributes which have getter, setter and delete methods like __get__, __set__ and __delete__ methods.
