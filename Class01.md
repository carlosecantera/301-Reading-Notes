# Reading Notes Class 01

## Component-Based Architecture

- What is a component? - A component is a pre-set function or object that accepts different kinds of information.
- What are the characteristics of a component? - There are three diferent views of a component.  Object-oriented view, in which a compnent is viewed as a set of one or more classes. Conventional view, is a functional element of a program that processes the logic and the internal data structures are required to implement the processing f the logic and them is enabled to be invoked and data to be pushed through it.  Latly Process-related view, is  viewed as a component that is already exisiting in a library.  Components are Reusable, replaceable, not content specific, extensible, encapsulating, and independent.
- What are the advntages of using componenet based architecture? It is easy to deploy, it cost less, easily developed, reusable, reliable, easy to manipulate, and because it is independent it is flexible.

## What is Props and How to Use it in React

- What is props short for? Props is short for "properties"
- How are props used in React? Props are used to pass data from one component to another.
- What is the flow of props? Props flow only in one direction or are uni-derectional which means the information flow goes from a parent component to a child component.  It should not flow up from a child to a parent because props are read-only.