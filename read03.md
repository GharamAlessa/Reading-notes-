# Passing Functions as Props
![](https://i.ytimg.com/vi/szmS_M-BMls/maxresdefault.jpg)
### What does .map() return?
>  the new array returned by map() to the variable doubled and log it

### If I want to loop through an array and display each value in JSX, how do I do that in React?
>  we loop through the array using the JavaScript map() function. We return a < li > element for each item. Finally, we assign the resulting array of elements to listItems

### Each list item needs a unique __*< ul > element*__.

### What is the purpose of a key?
> Keys help React identify which items have changed, are added, or are removed

[React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

### What is the spread operator?
> The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

### List 4 things that the spread operator can do.
> + Copying an array
> + Concatenating or combining arrays
> + Using Math functions
> + Using an array as arguments

### Give an example of using the spread operator to combine two arrays.
 
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩


### Give an example of using the spread operator to add a new item to an array.
![](https://miro.medium.com/max/756/1*mbZdAMcrXN8XpOSx7Gi7Ng.png)

[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

