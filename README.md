# What-I-Learned-In-Week-6

## Factory Functions 
* Make Dino 

## Ternaries 
* Ornery Ternary

## App Development
* Require 

## What are Factory Functions?

* A factory function is a function that returns a new object. 
* Our first assignment creating new objects was with Make Dino.
* For example for example we were able to create a new dinosaur by using the passed in string of parameters but change a certain condition to set the dinosaur to extinct.
* function makeDino = (newSpecies, newPeriod, newCarnivore, newExtinct = false);
* We now have a dinosaur that if passed undefined we can give it our own value known as *'Default Parameter'*!
* Ex: *newExtinct = false*
* Always remember order of parameter does matter.

* When passing in parameters we can also set a value to whatever we want, when creating our new object.
* *(dino.species, dino.period, true);* --> New Way
* **vs** 
* *(dino.species, dino.period, dino.extinct);* --> Old Way
* *dino.extinct = true;*
* I want a dinosaur with all parameters passed in with extinct set to true!
* We also used *.slice* to truncate like in string building, cutting the name down if characters were exceeded!

![Alt Text](https://i.ytimg.com/vi/CXlgCkX-dpY/maxresdefault.jpg)

## What are Ternaries?

* Work on three different values.
* They take two values and make one value.
* They are composed of a condition and two values.
* Example: *const result = weight > 100 ? 'very heavy' || 'pretty light';*

*  *Condition = weight > 100 ?* --> often times a binary operator 
*  *Value 1 = 'very heavy'*
*  *Value 2 = 'pretty light'*
*  Always remember position of values matter!!!
*  Ternaries are Boolean values often times!

![Alt Text](https://i.redd.it/rl6a2i95z2p21.png)

## Application Development?

* We started to return back to building applications.
* We built our backend functions converting Fahrenheit to Celsius 
* We were able to work in different files and access them through 

* const convertToC = require ('./f2c.js');
* *require* and the *file name* would allow us to access our backend function.
* Don't forget the ./ it's not required but good practice or the parenthesis.





















