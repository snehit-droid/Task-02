# Objects and its internal Representation in JavaScript
Objects, in JavaScript, is it’s most important data-type and forms the building blocks for modern JavaScript. These objects are quite different from JavaScript’s primitive data-types(Number, String, Boolean, null, undefined and symbol) in the sense that while these primitive data-types all store a single value each (depending on their types).

Objects are more complex and each object may contain any combination of these primitive data-types as well as reference data-types.
An object, is a reference data type. Variables that are assigned a reference value are given a reference or a pointer to that value. That reference or pointer points to the location in memory where the object is stored. The variables don’t actually store the value.

Loosely speaking, objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types, in the form of “key: value” pairs. These keys can be variables or functions and are called properties and methods, respectively, in the context of an object.
An object can be created with figure brackets {…} with an optional list of properties. A property is a “key: value” pair, where a key is a string (also called a “property name”), and value can be anything.

To understand this rather abstract definition, let us look at an example of a JavaScript Object :
'''javascript
let school = {
name : “Vivekananda School”,
location : “Delhi”,
established : “1971”
}
'''
In the above example “name”, “location”, “established” are all “keys” and “Vivekananda School”, “Delhi” and 1971 are values of these keys respectively.

Each of these keys is referred to as properties of the object. An object in JavaScript may also have a function as a member, in which case it will be known as a method of that object.

Let us see such an example :
// javascript code demonstrating a simple object
'''javascript
let school = {
name: ‘Vivekananda School’,
location : ‘Delhi’,
established : ‘1971’,
displayInfo : function(){
console.log(${school.name} was established
in ${school.established} at ${school.location});
}
}
school.displayInfo();
'''
Output:
In the above example, “displayinfo” is a method of the school object that is being used to work with the object’s data, stored in its properties.
Properties of JavaScript Object
The property names can be strings or numbers. In case the property names are numbers, they must be accessed using the “bracket notation”.

