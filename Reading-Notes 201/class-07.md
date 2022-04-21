## Domain Modeling
Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

var EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}

var parkourFail = new EpicFailVideo(7, false);
var corgiFail = new EpicFailVideo(4, true);

console.log(parkourFail);
console.log(corgiFail);

This is object-oriented programming in JavaScript at its most fundamental level.

-The new keyword instantiates (i.e. creates) an object.
-The constructor function initializes properties inside that object using the this variable.
-The object is stored in a variable for later use

## Tables
Basic table structure includes the following
- The table element is used to create a table.
- The TR tag indicates the start of each row  inside the TR tag you a TD element.
- The TD element stands for table data 
- The TH element is used just like the TD element but its purpose is to represent the heading for either a column or a row.

## Functions, Methods, and Objects
To create a function you give it a name and then write the statements needed to achieve its task inside the curly braces. This is know a function declaration