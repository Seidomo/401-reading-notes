### CLASS 01


## REVIEW, RESEARCH AND DISCUSS


- [**HOME**](https://seidomo.github.io/reading_notes/home)


``` array.map() ```

*array.map()* is a method that allows you to iterate over an array and take an action on every value in the array and get an new array.

``` array.reduce() ```

*array.reduce()* is a method that allows you to itarate over each element of the array resulting in a single accumulated value.

``` superagent() ```

*superagent()* is a node.js dependency that we rely on to get data from the internet.

*superagent() using .then()*

```
superagent.get(url)
     .then(data =>{
         console.log(data.body);
     }).catch(err => console.error(err))

```

*superagent() using async/await*

```
async function getData = () =>{
    let data = await superagent.get(url);
    console.log(data.body);
}

```

``` PROMISES ```

A promise is an object that once called upon will eventually resolve or reject
and return a response based on some creteria that is specific within the object.


*Are all callback functions considered to be Asynchronous?*

No not all call back functions are asynchronous some of them are and some of them are synchronous it depend on the function 


- [**back to home**](https://seidomo.github.io/reading_notes/home)