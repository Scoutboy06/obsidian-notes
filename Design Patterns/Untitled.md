Objects are created by instantiating a class. The object is said to be an *instance* of the class. The process of instantiating a class allocates storage for the object's internal data (made up of *instance variables*) and associates the methods with these data. Many similar instances of an object can be created by instantiating a class.

```TypeScript
class Circle {
	radius: number;

	// A built-in method in JavaScript. It is ran when creating a new instance of the object.
	constructor(radius: number) {
		this.radius = radius;
	}
}

// Create two separate instances of Circle
let circle1 = new Circle(20);
let circle2 = new Circle(100);
