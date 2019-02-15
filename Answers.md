# Answers

1.  What is React JS and what problems does it try and solve?

React JS is a library for building user interfaces. A problem that it tries to solve is one with DOM operations, React has a virtual DOM and when there are updats to the UI a diff is generated which compares the old DOM with the new virtual DOM only updates the items that have changed.

2.  What does it mean to _think_ in react?

To think in react means to break down the build into smaller more manageable pieces that can be reused.

3.  Briefly describe some of the differences between a Class/Stateful component and a Functional/Presentational component.

Class  component- Has state methods and a new instance of a class component is generated each time it's rendered. 

Functional component - Has no state methods that take props and return a react component.

4.  Describe state.

This is the key to components and determines how the components render and behave. This is what lets create components that are dynamic update in real time.

5.  Describe props.

Data that is passed down through props is used to render components with dynamic data.An example use of props would be to display data in a title as shown below:

<h1>{this.props.title}</h1>
 