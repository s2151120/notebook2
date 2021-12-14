# Data Abstraction
#icomsem1
Created: 2021-11-03 03:46

### Modular Design

Thinking about a piece of software made up of two components:

component A -> designed by someone
component B -> designed by someone else

The "interface" allows the components to be glued together neatly without fiddling around within the seperate components. 

Modular design is about the interface, making sure components can fit seamlessly. It's also about generalising components for other uses. 

To be able to interface with a module in Haskell, we can do this
`module MyModule
 	( MyType, myFunction, ...) where
	import YourModule`
	
Meaning we can filter the functions and types inside a module and extract exactly what we need.

The import issue:
If Module A relies on a function from Module B and Module C relies on a function from Module A then any small change in any module can ruin the system. Interfaces provide isolation of modules so that this is minimised. 

Modules should ideally be thought of as **black boxes** in that we should be able to take them out and replace them with other [[black boxes]].

## References
1. Chapter 21, see [[Computational Logic]]