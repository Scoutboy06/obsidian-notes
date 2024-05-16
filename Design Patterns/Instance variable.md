An instance variable is a part of an object's internal data.

```TypeScript
class Circle {
	// Instance variable called `radius`
	radius: number;
}

let circle = new Circle();

// Setting value of instance variable
circle.radius = 30;

console.log(circle.radius); // 30