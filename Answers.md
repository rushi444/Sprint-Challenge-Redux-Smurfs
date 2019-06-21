1.  Name 3 JavaScript Array/Object Methods that do not produce side-effects? Which method do we use to create a new object while extending the properties of another object?

map, filer, concat

spread (...)

1.  Describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

The store holds the state of the application and changes made to it.

The actions are the events that happen in your app.

The reducers are pure functions that take in two arguements (current state and action) to give us one object.

1.  What is the difference between Application state and Component state? When would be a good time to use one over the other?

Component state is the state only in that component, you would use it in a form.

Application state holds the state that is used my different views and components

1.  What is middleware?

Middleware will intercept an action before it reaches the reducer and run a function.

1.  Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

Redux thunk allows us to handle async operations inside our action creators.

1.  Which `react-redux` method links up our `components` with our `redux store`?

connect()
