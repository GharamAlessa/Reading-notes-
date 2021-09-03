#  React and Forms
![](https://res.cloudinary.com/practicaldev/image/fetch/s--KpQnReJ9--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://i1.wp.com/blogreact.com/wp-content/uploads/2020/03/forms.jpg%3Ffit%3D750%252C393%26ssl%3D1)
### What is a ‘Controlled Component’?
> it is an element in a form that whose value is controlled by react.
Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
as soon as the user enter them because the value of the input should update as the user types.

### How do we target what the user is entering if we have an event handler on an input field?
> by using the event.target.value in the eventhandler function and updating the value attripute.
The Conditional (Ternary) Operator Explained

### Why would we use a ternary operator?
> it has less lines of code and easier to follow.

### Rewriting the following statement using a ternary statement:
if(x===y){

console.log(true);

} else {

console.log(false);

}

it would become
x===y?console.log(true):console.log(false);


#### read more:
+ [React Bootstrap - Forms](https://react-bootstrap.github.io/components/forms/)
+ [React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)
