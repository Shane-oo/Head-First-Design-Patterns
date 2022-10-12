Object-oriented programing and UML terminology.
1. A House <b> is a </b> building (inheritance);
2. A House <b> has a Room </b> (composition);
3. A House <b> has an </b> occupant (aggregation)

The difference between (2) and (3) is subtle yet important to differentiate. Together they are forms of association. What's the difference? Composition implies the child object cannot live out of the context of the parent (destroy the house and rooms disappear) whereas aggregation implies the child can exist on its own (destroy the house and the occupant goes elsewhere).

<b> The Strategy Pattern </b> defines a family of algorithms, encapsulates each one, and makes them interchangeable. Strategy lets the algorithm vary independently frim clients that use it.
