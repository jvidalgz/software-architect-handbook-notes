# The Meaning of Software Architecture
## What is software architecture?
* Consists of early design decisions that can be difficult to change later
### ISO/IEC/IEEE 42010 standard definition
 > Fundamental concepts or properties of a system  in its environment embodied in its elements, relationships, and in the principles of its design and evolution.
 >
 * The standard makes the following main points:
    * A software architecture is a fundamental part of a system
    * A software system is situated in an environment, and its software architecture takes into consideration the environment in which it must operate
    * An architecture description documents the architecture and comunicates to stakeholders how the architecture meets the system's needs
    * Architecture views are created from the architecture description, and each view covers one or more architecture conecerns of the stakeholders
### What makes up a software architecture?
* A software system contains structures, and a software system is made up of one or more of them. It is the combination of these that forms the overall software architecture. A large software project may have multiple teams working on it each responsible for a particular structure
### Software architecture is an abstraction
* Is an abstraction of a software system
* The structures of a software system consists of its elements. Software architecture concerns itself with defining and detailing the structures, their elements, and the relationships of those elements with each other.
* Software architecture focuses on the public aspects of the elements, and how they interact with each other. For elemetns, this may take the form of their public interfaces. It does not deal with the private implementation details of the elements. While the behavior of the elements does not have to be exhaustively documented, care should be taken in understanding how elements have to be designed and written so that they can properly interact with each other.