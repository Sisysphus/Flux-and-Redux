<h1 align='center'>
Flux and Redux
</h1>

Redux is an evolution of the concepts introduced by flux.

Having a general understanding of Flux will help you understand Redux.

<h1 align='center'>
What is Flux?
</h1>

Flux is a front-end application architecture Facebook developed to use with React.

Flux is not a library or framework.

Flux is simple a pattern in which to structure one's application.

It doesnt even need to be used with React!

Flux provides unidirectional data flow.

Unidirectional data flow affords more predictability than one might encounter when using other applications design patterns.

<h1 align='center'>
Actions
</h1>

An action begins the flow of data in Flux. An action is a simple object that at a minimum contains a type.

An actions type indicates the type if change to be performed on the application's state.

An action may contain additional data (the "payload") that's necessary for changing the applications former state to the next one.

<h1 align='center'>
Dispatcher
</h1>

The dispatcher is a mechanism for distributing(or "dispatching") actions to a Flux application's store.

The dispatcher is a little more than a registry of callback functions into the store.

Redux consolidated the dispatcher into a single dispatch() function.

<h1 align='center'>
Store
</h1>

The store represents the entire state of the app.

The store is also responsible for updating the state of the app whenever is recieves an action.

It does so by registering with the dispatcher a callback function that recieves an action.

This callback function uses the actions type to invoke the proper functions to change the apps state.







