# Redux Quiz

<img src="https://chriscourses.com/img/blog/redux/redux.jpg" height="400px"/>

## Getting Started

- Fork and Clone

## Questions

1. What is Redux?

```
Redux is an external state management library that can be integrated with UI frameworks such as React and Angular.
When used with React, we can extract state outside of our React components into a global store and import the slivers of state that we need inside of our React components.
```

2. What packages do we install to use Redux?

```
To use Redux, we run npm install redux. We also install react-redux to integrate React with Redux.
```

3. In your own words, describe the flow of how Redux is used to manage state.

```
Redux enables us to extract state outside of our components and into a global store, instead of maintaining state inside of those components. Components accept the data as props.
```

4. What do we use in order to manage different pieces of state?

```
To manage different pieces of state, we use reducer functions, which break our state up into separate modules.
```

5. What do we use to perform an update to state?

```
To perform an update to state, we dispatch actions.
```

6. How do we access state from Redux?

```
We access state from Redux in our components via props. The react-redux connect function allows container components to interact with the store. Using mapStateToProps, connected components can extract specific slivers of state from the store state.
```

7. In your own words, describe how to set up Redux for a React App.

```
First, install redux and react-redux dependencies by running npm install react-redux redux.
Inside of the src/ folder, create directories for actions/ and reducers/, as well as an index.js file and a types.js file.
In src/index.js, we create the store using createStore import from redux. In the React app's index.js file, we connect our Redux store to our React app using the Provider component from react-redux. The Provider component accepts store as a prop and wraps our App component.
```

## Submission

Pull Request due by **9AM EST** following the [PR Submission Guidelines](https://github.com/SEI-R-2-22/template_pull_request).
