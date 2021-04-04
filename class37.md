### CLASS 37


# Redux - Combined Redux






## REVIEW, RESEARCH AND DISCUSS


- [**HOME**](https://seidomo.github.io/reading_notes/home)


### Why choose Redux instead of the Context API for global state?



### What is the purpose of a reducer?

- A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. We have tools, like Redux, that help manage an application's state changes in a single store so that they behave consistently.


### What does an action contain?


- Actions have a type field that tells what kind of action to perform and all other fields contain information or data. And there is one other term called Action Creators, these are the function that creates actions. So actions are the information Objects and action creator are functions that return these actions.


### Why do we need to copy the state in a reducer?

- We need a copy of the data because if the data changes outside of the store so that it wont change the data inside the store.



## TERMS:


``` immutable state ```


- Immutable state is state that cannot be changed. Immutable objects for which none of the state can be changed become important when you are dealing with concurrency, the ability for more than one processor in your computer to operate on that object at the same time.



``` time travel in redux ```

- A scalable undo redo time travel implementation that leaves your original state intact



``` action creator ```

- An action creator is merely a function that returns an action object. ... Calling an action creator does nothing but return an object, so you have to either bind it to the store beforehand, or dispatch the result of calling your action creator.



``` reducer ```

- A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. 


``` dispatch ```

- Dispatch has access to currentState and reducer . When dispatch is called, it receives an action object as an argument. ... when an action is dispatched, or when we invoke dispatch and pass in an action object, the dispatch function calls our reducer and passes in the current state and the action object




[**BACK**](https://seidomo.github.io/reading_notes/home)