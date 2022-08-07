AirBnB_clone
---
Description
---
<br>
This team project is part of the Holberton/ALx  School Full-Stack Software Engineer program. It's the first step towards building a first full web application: an AirBnB clone. This first step consists of a custom command-line interface for data management, and the base classes for the storage of this data.
<br>
Writing A Command Interpreter(The Console)<br>
---
This console is written in Python3, and will be used to do CRUD operations (Create, Read, Update, Delete) on our AirBnB objects (User, City, Review, etc.). More information on the models will be described in the later section.
<br>
**Models**<br>
---
<br>
At the moment, we have 7 models: BaseModel, User, State, City, Amenity, Place, and Review, each instance of which is given:<br>
+ a unique id generated using ``` uuid ``` package<br>
+  ```created_at```, a ```datetime``` object, indicating when the object is created<br>
+ the attribute ```updated_at```, a ```datetime``` object, indicating when the object is last<br>
+ the attribute ```__class__```, a ```str``` object, indicating what is the object's type (model)<br>

AUTHORS
---
+ Richard Ouma
+ Rachael Kivuti

