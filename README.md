Project Description
This program is an object-oriented implementation of a bag data structure using linked nodes in Java. A bag is a collection that allows duplicate elements and does not enforce any particular order. The project includes the following components:

LinkedBag Class:

Implements the bag data structure using a chain of linked nodes.
Supports operations such as adding elements, removing elements (specific or arbitrary), checking for duplicates, counting frequencies, and testing for membership.
Includes additional methods for:
Removing duplicates (removeDuplicates()).
Duplicating all elements (duplicateAll()).
Checking equality between two bags (equals()).
BagInterface:

Defines the operations that a bag must implement, ensuring a consistent API for different implementations (e.g., array-based or linked-based).
BagExtensionsTest:

Contains tests to verify the correctness of the LinkedBag implementation.
Tests methods like equality, removal of elements, duplication of all elements, and removal of duplicates.
Includes scenarios with varying bag sizes, duplicate counts, and empty bags to ensure robustness.



Key Learning Outcomes
Object-Oriented Programming Principles:

Learned to design modular and reusable code by separating the interface (BagInterface) and implementation (LinkedBag).
Applied encapsulation by using private variables and inner classes (e.g., Node).
Data Structures and Algorithms:

Gained experience with linked data structures and their advantages over array-based implementations.
Explored methods for handling duplicates and maintaining collection integrity.
Testing and Debugging:

Practiced systematic testing through comprehensive test cases in BagExtensionsTest.
