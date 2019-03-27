# Polymorphism
## What does the word 'polymorphism' mean?
- Many Forms

## What does it mean when we apply polymorphism to OO design? Give a simple Java example.

- We take something of a certain type/Class and group it with different type/classes which can then all be stored together in an arrayList

- Car car = new Car("Mini")
- Couch couch = new Couch("Leather")

- ArrayList<ISell> sellableItems = new ArrayList<ISell>();

- sellableItems.add(car)
- sellableItems.add(couch)

## What can we use to implement polymorphism in Java?

- Interfaces and Parent classes

## How many 'forms' can an object take when using polymorphism?

- there is no limit to how many forms

## Give an example of when you could use polymorphism.

- if we had a dog and a human we could apply an interface of IWalk which would mean we could pass them around our program as type IWalk even though they are both different Classes.

# Composition
## What do we mean by 'composition' in reference to object-oriented programming?

- Breaking up our program into the smallest possible parts

## When would you use composition? Provide a simple example in Java.

- When Creating an Object for example a computer which might be made up of multiple components e.g. mouse, keyboard, monitor

- Mouse mouse = new Mouse()
- Keyboard keyboard = new Keyboard()
- Computer computer = new Computer(keyboard, mouse)

## What is/are the advantage(s) of using composition?

- It makes our program more scalable and easier to implement new features

When an object is destroyed, what happens to all the objects it is composed of?
