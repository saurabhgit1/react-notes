1. states and codes (life cycle hooks) were earlier exclusive to class components.
   Functional components didn't have all these.

2. After React 16, states and life cycle hooks are available to funcitonal components as well in form of hooks.

3. JSX - Javascript XML - extension to js lang syntax. - ultimately transpiles to pure JS for browsers.
4. Can write react without JSX using React.createElement()
5. JSX difference-> class -> className
   for -> htmlFor
   camelcase propery name
   onclick -> onClick
   tabindex -> tabIndex
6. props.children
7. this.props.propname -> for class components
8. props are immutable
9. setState is async, use callback to do after value is updated.
10. when you want to update the state based on previous value, use callback to update. props can also be sent in the callback as 2nd arg.

11. in class components, there are different ways to bind to event handlers
    bind, arrow functions, bind in class constructor, class prop as arrow function (benefit of lexical scoping).
12. in class components, we have to bind the function with this because when we are using it as a event handler it is getting called in different context. this can become detached. in order to avoid the detachment, we bind explicitly.

13. When you declare a method as an arrow function in a class component, you don't need to explicitly bind this because arrow functions capture the value of this lexically from the enclosing context. This behavior contrasts with regular functions, where the value of this is determined by how the function is called.

Here's why arrow functions eliminate the need for explicit binding:

Lexical this: Arrow functions do not have their own this context. Instead, they inherit this from the enclosing scope in which they are defined. In the case of a class component, the arrow function inherits this from the class instance. This behavior is known as lexical scoping or lexical this binding.

Binding at Declaration: Regular functions have their own this context, which is determined by how they are called. When you define a method in a class component using a regular function syntax, you need to explicitly bind this to the method in the constructor to ensure that this refers to the class instance when the method is called.

## conditional rendering
14. using if-else , using ternary operator, using shor-circuit operator

## list rendering
15. using map return html elements

## basics of form handling

## lifecycle methods

## context API
context provides a way to pass data through component tree without having to pass props down manually at every level
