1. Polymorphism comes from the greek 'poly' meaning many and 'morph' meaning form/shape so polymorphism means many forms.

2. In OO polymorphism refers to the practice of allowing an object to be treated as many different classes base on the situation in which it is required.
```Dog dog = new Dog(); //Dog being a child of a superclass animal
    Animal dog = new Dog() //Dog may also be created as an Animal object through inheritance using polymorhism```

3. Polymorphism may be implemented through the use of both inheritance and application of interfaces where an object may be called as an instance of the interface Class e.g a dog could be called as an instance of IBark.

4. An object can take as many forms as are required by the use case depending on the situation, though a class may only inherit from one class that superclass may inherit from another parent class so the initial child could be an instance of any parent class. With interfaces however, as many interfaces as are necessary can be implemented by a class and objects can be instantiated as any type from the interfaces that the class implements.

5. A potential use case for polymorphism would be the ability to include multiple different child classes in one collection by instantiating them as instances of a common parent class e.g.
Lizard, Flamingo and Kangaroo could all be added to an Arraylist<Animal> if they all inherited from an Animal superclass.

6. Composition is the idea of creating a Class by amalgamating all the parts that make up a Class as subclasses which become attributes of the combined class.

7. Composition would be useful to model anything that is made up of definable sub pieces e.g. a car or other machine that has components which come together to 'compose' the whole.

8. Aggregation suggests a relationship where a child may exist without the associated parent class whereas Composition suggests a relationship where the existence of the child depends on the existence of the parent e.g. Aggregation = A guitarist in a band, the guitarist would still exist if the band were to break up vs Composition = A room in a house, A room cannot exist outside of its contained building and its existence is entirely predecated on the existence of the house, should the house be destroyed so too is the room.

9. the advantages of composition and aggregation over inheritance are that: composition is more flexible tham inheritance, less likely to have a rigid class heirarchy which may be difficult to manage and easily adheres to encapsulation which allows code to be more manageable because each composite part is only dealing with the tasks that it is responsible for.

10. WHen using composition, all children are destroyed if the parent is destroyed.

11. When using aggregation, the children will continue to exist even if the parent is destroyed.

