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