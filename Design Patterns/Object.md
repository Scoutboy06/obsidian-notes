An object packages both data and [[Method|methods (procedures, operations)]] that operate on that data. Objects are created by [[instantiating a class]].

## Class

An object's implementation is defined by its *class*. The class specifies the object's internal data and representation and defines the [[Method|methods]] the object can perform.

```TypeScript
class SomeClass {
	data: number;

	void someMethod() {
		this.data = 3;
	}
}
```

## Instance variables

An instance variable is a part of an object's internal data.

```TypeScript
class Circle {}
```