###Time to practice some UML diagrams!

There are systems all around us, so let's model one that we should all be familiar with: a 4-way traffic light intersection. We know that the purpose of the system is to get people through the intersection without collision and as efficiently as possible. 

Here is what you need to do:
* Make a list of boundary objects. These should be easy to identify since they are the objects that actors interact with.
* Make a list of control objects. These will be a little trickier as we usually don't see them. Think about what software, wiring, or other control mechanisms are necessary to make the system work. Remember that boundary objects can generate data, but in order to store that data in an entity object it must pass through a control object. Give them names based on the function they are providing. Remember that objects are always nouns.
* Make a list of entity objects. These are objects that store data. Think about what data needs to be stored for the system to work. Give them names based on the data they are storing. Remember that objects are always nouns.
* Make a list of primary actors. These are the actors (outside the system) that interact with the system in its intended manner. They initialize the interactions themselves.
* Make a list of secondary actors. These are the actors (outside the system) that interact with the system in some other manner. They often respond to something the system does.
* Make a Use Case diagram. This should be pretty high level. We are thinking about how the system is being used, not the finer details of its implementation.
* Make a Class diagram. This should be a bit lower level. What are the different classes? What methods and fields do they have? What are their relationships to one another? Remember that classes are nouns and that actors are **not** included. Look at your boundary, entity, and control objects for ideas. These could be classes or you combine or seperate them into different classes.
* Make a Sequence diagram. This should show how the system operates in a particular case. Let's start the sequence diagram with a car driving up to a red light. What does the system do? What checks does it make (if statements)? How do the different components interact? Should it loop anywhere? This diagram only models one use case, so do not include other possible use cases in the diagram.