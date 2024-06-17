# Object-Oriented-Analysis-Design-Review-5


## Concurrent behavior

What is a concurrent behavior?
- A construct to specify the external behavior of objects in object databases
- In use case diagram, an actor is drawn as cuncurrently act on all activities

To document ____, draw a composite state with the lower portion divided into multiple compartments for each concurrent path of behavior.
- concurrent behavior of a single object


## Object oriented approach

- focuses on objects that represent abstract or concrete things in the real world
- objects are first defined by their character and their properties

In the object-oriented approach to systems development, the flow of information is achieved by sending messages either to and from actors or back and forth between internal objects.
- True

One of the disadvantages of UML and object-oriented models is the difficulty of synchronizing the models
- False

Which of the following is NOT an advantage of object-oriented modeling with several models is that _____.
- developing new models allows the analyst to discard unnecessary diagrams.

Since an activity diagram is not object-oriented (e.g. no objects), it is not a standard model of the object-oriented Unified Modeling Language (UML)
- False


## Activity Diagram

The diagram model that is useful to document the flow of activities on a fully developed use case description is called a(n) _______.
- activity diagram

In a fully developed use case description, the flow of activities is most similar to what?
- An activity diagram

In an activity diagram, a separate use case may used as part of the workflow.
- True

On an activity diagram, the diamond represents an "AND" condition
- False

Activity diagrams are not helpful when the flow of activities is too complex
- False

An activity diagram and the flow of activities in a fully developed use case description serve the same purpose
- True

Activity diagrams cannot be used to describe processes that involve automated system activities
- False

An oval indicates an embedded use case inside of an activity diagram
- True

Synchronization bars are used to indicate looping in an activity diagram
- True


## UML Alt & Opt fragment

An Opt frame and an Alt frame do essentially the same thing
- False

An Opt frame and a true/false condition on a message serve essentially the same purpose
- True

Note: UML - Sequence diagram Alt vs Opt
- alt - if else
- opt - single condition


## Interaction Diagram

In an interaction diagram, messages are sent and received by individual objects, not by classes.
- True

Two types of interaction diagrams are:
- Sequence diagrams/Communication diagrams


## Sequence Diagram

Two methods to show a return value in a sequence diagram are:
- Dashed arrow with value "---value-->"
- value ":="

What is the difference inbetween interaction diagram and sequence diagram?
- The sequence diagram is a subset of interaction diagram

A true/false condition on a sequence diagram indicates whether the message can be processed or not
- False

In a sequence diagram, a message is considered to be an action that is invoked on the destination object
- True

On a sequence diagram when multiple messages are included within a repeating loop a(n) _______ is used to document it.
- loop frame

In UML terminology in a sequence diagram, a message refers to a(n) _______.
- action

To show if-then-else condition on a sequence diagram use a(n) ______.
- alt frame

On a sequence diagram, a message represents a service request
- True

In a sequence diagram, a message is considered to be an action that is invoked on the destination object.
- True

In a sequence diagram the message-name is usually given in what format?
- verb-noun

A true/false condition on a sequence diagram indicates whether the message can be processed or not.
- False


## Sequence Diagram - Asterisks

A loop frame and an asterisk mean the same thing in a sequence diagram
- True

Two methods to show a repeating message are:
- Asterisk */Loop frame

On a sequence diagram a short notation that indicates a repeating message is a(n) _______.
- loop frame/asterisk


## System Sqauence Diagram

What is the difference inbetween sequence diagram and system sequence diagram?
- The system sequence diagram is a subset of sequence diagram

A diagram that shows the messages between an actor and the system is called a(n) _______.
- system-sequence diagram

Activity diagrams are not helpful in developing system sequence diagrams (SSDs).
- False

Briefly describe the purpose of a system sequence diagram.
- to illustrate the use case in a visual format

Information for Use Case Descriptions is primarily derived from System Sequence Diagrams
- False

In a system sequence diagram the order of the messages is determined by numbering the messages
- False

In a system sequence diagram a box refers to a class of objects
- False
An arrow on a system sequence diagram is used to depict a(n) what?
- message


## Use case diagram / System Sqauence Diagram

An actor is always outside of the automation boundary in a use case diagram
- True

The ____ are the primary models from which other models draw information.
- use case diagram
- problem domain class diagram

An action-expression occurs when:
- Before the object enters the destination state.

Another way to think of a actor using a use case is as a(n) _______.
- role

## Use cases in pre & post-condition

Two difference scenarios of a use case would normally be described in a single fully developed use case description.​
- False

A good way to describe a use case scenario is with a state chart
- False

A textual model that describes the processing details of a use case is called a(n) ________.
- use case description

A unique set of internal activities within a use case which represents a unique path through the use case is called a(n) _______.
- scenario

A certain set of values or statuses that must exist after a use case completes its processing is called a(n) _______.
- post-condition

In a fully developed use case description normally the preconditions describe what?
- What objects must exist prior to the use case executes.

In a fully developed use case description the exception conditions represent what?
- What conditions prevent the system from successfully completing the use case.

In a fully developed use case description the postcondition data describes what conditions?
- The existence of domain model objects.

A certain set of values or statuses that must exist before a use case begins is called a(n) _______.
- pre-condition

For real-world objects the state of an object is the same as its _______ .
- status condition

A condition during an object's life when it satisfies some criterion is called a(n) _______.
- state

A true/false condition on a message indicates the condition of the return value of the message, i.e. whether the message was successful or not
- False


## CRUD technique

What does CRUD mean?
- Create, read, update and delete
- Four basic functions that models should be able to do

The best use of the CRUD technique is used to generate new use cases
- False, used to make sure the list of use cases covers all of the processes

The CRUD technique can be used to identify new use cases as well as delete unnecessary use cases
- True

In using the CRUD technique, new use cases and new stakeholders may be identified
- True


## State machine diagram

The beginning state of an object when its states are diagrammed is called a(n) _______.
- pseudo-state

In a state machine diagram when one state is high-level in that it contains other states of an object, it is called a(n) ______.
- composite state

In a transition label in a state machine the syntax is A(B)\[C\]/D. The D stands for what?
- action expression

A UML diagram that shows the life of an object in states and transitions is called a(n) _______.
- state machine diagram

In a state machine diagram, a state is represented by a(n) ____.
- oval

A state machine diagram is used to document the states and transitions of a(n) ________.
- Object

Which of the following documents information about classes that are part of the problem domain of the user?
- State machine diagram

When an object moves from one state to another the ending state is called a(n) _______ .
- destination state

Which of the following is NOT an element in a transition label?
- trigger

The guard-condition on a transition indicates what?
- Whether the transition fires.
