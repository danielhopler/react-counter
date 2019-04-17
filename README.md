# react-counter

* A simple tutorial from the [Bloc Web Developer Program](www.bloc.io) to cut your teeth on React.js components, state and props.
* React documentation - https://reactjs.org/

## Configuration
* Include the required libraries/ scripts hosted by [CDNJS](https://cdnjs.com/) in `greeting.html`
```
<!DOCTYPE html>
<html>
  <head>
    <title>My First React App</title>
  </head>
  <body>
     <p>Hello world!</p>
     <div id="app"></div>
     <script src="https://cdnjs.cloudflare.com/ajax/libs/react/16.1.0/umd/react.development.js"></script>
     <script src="https://cdnjs.cloudflare.com/ajax/libs/react-dom/16.1.0/umd/react-dom.development.js"></script>
     <script src="https://cdnjs.cloudflare.com/ajax/libs/babel-core/5.8.34/browser.min.js"></script>
     <script type="text/babel">
 
     </script>
  </body>
</html>
```

* We need to load three libraries: react, react-dom, and babel-core. We need the first two to render React into a DOM, and the third to enable JSX and ES6. Next, we will write the rest of our code in a <script> block. We'll use the  text/babel format to enable ES6. Babel is a JavaScript compiler that allows us to use the latest generation of JavaScript.
  

