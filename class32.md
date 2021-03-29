### CLASS 32


# Custom Hooks






## REVIEW, RESEARCH AND DISCUSS


- [**HOME**](https://seidomo.github.io/reading_notes/home)



### What does a component’s lifecycle refer to?

- Each component in React has a lifecycle which you can monitor and manipulate during its three main phases. The three phases are:

- ``` mounting ```

- ``` updating ```

- ``` unmounting ```


### Why do you sometimes need to “wrap” functions in useCallback when called from within useEffect


- useCallback will help in avoiding regeneration of functions when the functional component re-renders. However there isn't much of a performance difference caused by recreation of functions.


### Why are functional components preferred over class components?

- Functional component are much easier to read and test because they are plain JavaScript functions without state or lifecycle-hooks.



### TERMS:


``` state hook ```

or useState()  allows you to use state and other React features without writing a class. Hooks are the functions which "hook into" React state and lifecycle features from function components.


``` effect hook ```

or useEffect() tells your component needs to do something after render. React will remember the function you passed, and call it later after performing the DOM updates.


``` reducer hook ```

or useReducer() is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one.


[React Docs](https://reactjs.org/docs/hooks-reference.html)



- [**HOME**](https://seidomo.github.io/reading_notes/home)