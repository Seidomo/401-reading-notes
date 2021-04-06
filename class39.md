### CLASS 39


# Additional Topics






## REVIEW, RESEARCH AND DISCUSS


- [**HOME**](https://seidomo.github.io/reading_notes/home)


### What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?

- The best practice would be to use the useEffect ot load at start.

### When using a thunk/async action that dispatches the actual action, which do you export from your reducer?

- Export the function itsef.


## TERMS:


``` middleware ```

- Is a function that provides a medium to interact with dispatched action before they reach the reducer.


``` thunk ```

- Is a middleware that allows you to write action creators that return a function instead of an action.



[**BACK**](https://seidomo.github.io/reading_notes/home)