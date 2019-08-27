# Design-Patterns-Tutorial-Strategy
Avoid interfaces that just force action. Forcing the creation of methods is a bad idea.
Superclass creates a public instance variable of type interface. Strategy of the strategy pattern is to define a family of algorithms, encapsulate each one, and make them interchangeable. The superclass and all of its subclasses can now dynamically switch between this family of algorithms.

Use the strategy pattern when you need to define a class that will have one behavior similar to other behaviors in a list. If you need a class object to choose from one of several behaviors dynamically, then use the strategy pattern. Also use it when there are a long line of conditionals as it avoids duplicate code, keeps class changes from forcing other class changes, and can hide complicated code from the user.
