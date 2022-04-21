## Public Domain, Objects and the DOM
a quick breakdown of the chapter, the author talks about the importance of learning the problem domain, if you can learn the public domain learing to program becomes easier.
If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things
- Make the problem domain easier
-Get better at understanding the problem domain
-make sure you understand a problem inside and out before you try and solve it with code.

I enjoyed the analogy he used about looking at a problem domain like a jigsaw puzzle and starting off with sorting the matching color pieces, and then the border pieces and then putting everything together. It is the same thing with code you put one piece together one at a time.

## Whats the difference between primitive values and and object references in JavaScript?
Primitive values and object references are stored in JavaScript programs in different ways, when a primitive to a value is assigned to a variable  the variable is set to that value directly 
when the variable is assigned with an object things are different , instead of containg the value directly the variable contains a reference to it like the example below.
const moe = {
  name: 'Moe Szyslak',
  occupation: 'Bartender',
  voicedBy: 'Hank Azaria'
}

when that code is ran JavaScript creates the object and stores it somewhere in the computer memory, the variable "moe" does not contain the new object directly , it contains a reference to the memory address that currently stores the object.

## Chapter 3 "Object Literals"
I found this chapter interesting, it shows us how to create objects using literal notation and this is shown on the example below 
var hote l = {
name: 'Quay',
rooms: 40,
booked : 25,
checkAvailability: function() {
return this.rooms - this.booked;
}
} ;
JAVASCRIPT
var el Name = document .getElementByld('hotelName');
elName.textContent =hotel .name;
var elRooms = document.getElementByid{'rooms');
elRooms.textContent = hotel .checkAvailability(); 