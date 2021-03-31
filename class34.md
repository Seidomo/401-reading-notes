### CLASS 34


#  ``` <Login /> and <Auth />






## REVIEW, RESEARCH AND DISCUSS


- [**HOME**](https://seidomo.github.io/reading_notes/home)



### Why is the Context API useful?

-Context API is useful because it enables components to share some data without explicitly passing via each component manually


### Can a component outside of a provider get its context?

- No to recieve it should be subsribed to the provider.


### What are some common use cases for using the Context API?

- Settings, themes, authentication, authorization.


- Describe 

- ``` Context Hell ``` 

- Is when you have too many contexts and you have hard time tracking them


## TERMS:


- ``` global state ```


- global state is where you put information when many components need access to the same stateful information


- ``` global context ```

- In a typical React application, data is passed top-down via props, but such usage can be cumbersome for certain types of props that are required by many components within an application. Context provides a way to share values like these between components without having to explicitly pass a prop through every level of the tree.


- ``` provider ```

- The Provider component accepts a value prop to be passed to consuming components that are descendants of this Provider. One Provider can be connected to many consumers. Providers can be nested to override values deeper within the tree.


- ``` consumer ```

- A consumer is a react component that subscribes to context changes. Using this component lets you subscribe to a context within a function component.


- [**HOME**](https://seidomo.github.io/reading_notes/home)

