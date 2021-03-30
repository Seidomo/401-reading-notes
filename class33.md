### CLASS 33


# Context API






## REVIEW, RESEARCH AND DISCUSS


- [**HOME**](https://seidomo.github.io/reading_notes/home)


### Describe use cases for: 

``` useMemo() ```

- usememo is a React hook that memorizes the output of a function. That is it. useMemo accepts two arguments: a function and a list of dependencies. useMemo will call the function and return its return value.

``` useReducer() ```

- Is a reducer function with the application initial state, returns the current application state, then dispatches a function.


### Why do custom hooks need the use prefix?

- Its used as a convention and also to let other developers the react is in use.

### What do custom hooks usually do?

- Custom hooks allow you to create functionality that can be used across different components with the ability to hook into component lifecycles and state.



### Using any list of custom hooks, research and name one that you think will be useful in your applications

- useEffect will tell the component to do something after the render.


### Describe how a hook that fetches API data might work

- First fecth the data using the url and then changing the state by using the useEffet by the data recieved from the api.


## TERM:

``` reducer ```


- A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. 



- [**HOME**](https://seidomo.github.io/reading_notes/home)