# Design-Patterns
Real time Examples of most used design patterns

### 1. Creational
 *Way of creating objects.*

**1.1 Prototype** : A fully initialized instance to be copied or cloned.
Example : initial status of chess game

**1.2 Builder** - Separates the construction of a complex object from its representation so that the same construction process can create different representations.
Example : when we make (or order) a pizza(it can de deferent in size and flavours )

**1.3 Singleton** - A class has only one instance and provides a global point of access to it.
Example : President of a country

**1.4 Factory Method** - Creates a family of object types.
Example : In an organisation HR works as factory method. Here development team request type of resource need to HR. Based on request type, HR provide resource to Development team.

**1.5 Abstract Factory** - Creates an instance of several families of classes
Example : HP, Samsung and Dell laptops are uses Intel and AMD processor.

### 2. Structural
*This design patterns is all about Class and Object composition i.e. How do you want structure the software component. This helps us guarantee that when one of the parts changes, the entire structure does not need to change.*

**2.1 Proxy** - An object representing another object.
Example : check book leaf, credit card, debit card are proxy for Money and a customer representative to order a product.

**2.2 Composite** - Gives an unified interface to a leaf and composite.
Example : File System in Operating Systems, Directories are composite and files are leaves. System call Open is single interface for both composite and leaf.

**2.3 Decorator** - Gives additional feature to objects, while giving unified interface.
Example : 1) Adding discounts on an order 2) gun is a deadly weapon on it's own. But you can apply certain "decorations" to make it more accurate, silent and devastating.

**2.4 Facade** - Single interface that represents entire subsystem.
Example : Control Panel, Event Manager.

**2.5 Adapter** - Provides different interfaces for an interface.
Example : Power Adapters

**2.6 Flyweight** - A fine-grained instance used for efficient sharing
Example : The Flyweight uses sharing to support large numbers of objects efficienthttps://refactoring.guru/design-patternsly. The public switched telephone network is an example of a Flyweight. There are several resources such as dial tone generators, ringing generators, and digit receivers that must be shared between all subscribers. A subscriber is unaware of how many resources are in the pool when he or she lifts the handset to make a call. All that matters to subscribers is that a dial tone is provided, digits are received, and the call is completed.

### 3. Behavioral
*This design patterns specially concerned with communication between Objects.*

**3.1 Chain of Responsibility** - A way of passing a request between a chain of objects
Example : Loan or Leave approval process, Exception handling in Java.

**3.2 Iterator** - Sequentially access the elements of a collection
Example : Next/Previous buttons on TV

**3.3 State** - Alter an object's behaviour when its state changes
Example : A fan wall control

**3.4 Observer** - A way of notifying change to a number of classes
Example : Bidding or auction, Publish/Subscribe

*3.5 *Visitor** - Defines a new operation to a class without change. Example : Taxi

**3.6 Template** - Defines a skeleton of an algorithm in an operation, and defers some steps to subclasses.
Example : A blue print

**3.7 Command** - Encapsulate a command request as an object
Example : The "Guest Check" at a diner is an example of a Command pattern. The waiter or waitress takes an order or command from a customer and encapsulates that order by writing it on the check. The order is then queued for a short order cook. Note that the pad of "checks" used by each waiter is not dependent on the menu, and therefore they can support commands to cook many different items.

**3.8 Memento** - Capture and restore an object's internal state
Example : save the state in a game & Undo/Redo operation in Windows

**3.9 Mediator** - Defines simplified communication between classes
Example : Air Traffic Controller(ATC)

**3.10 Strategy** - A Strategy defines a set of algorithms that can be used interchangeably.
Example : Modes of transportation
