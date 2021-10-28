##  Node lite server
Used to see live chances in the browser, as we modify our html files. 
## Package.json
* Used to define project dependencies and versions of each package needed.

## NPM init
* Used to initialize the package.json file.

## Install package for development dependencies

```npm install lite-server --save-dev```

## start Nodejs app
```npm start```

## Why JS Javascript Libraries/ Framework

* JS Frameworks extremely helps during DOM Manipulation. 
* Are very helpful to structure web application while using popular software architecture like MVC. 
* Framework offers generic functionality that can be selectively hanged by additional user-written code.
* Library: collection of function.
Frameworks: particular implementation of web application where our code fills in the details. 

## Imperative approach vsDeclarative Programming
* Imperative, steps by steps we defines the actions needed to reach a goal.
* Declarative approach: we state ust our goal. 

## React
* JS Library for building User Interface, using Declarative approach, and being component based and technology stack agnostic (can be used independently from technology and approaches used to build our web app).


## Terminology to learn:
* One way data flow:
In ReactJS, data flows in one direction, from Parent to Child. Consider React components as simple functions that receive props and state and return HTML. When child components receive props from their parents, they either apply modifications (render) or pass it to another child that may use it.


* JSX:

* Components: Components are independent and reusable bits of code. They serve the same purpose as JavaScript functions, but work in isolation and return HTML.
```
class Car extends React.Component {
  render() {
    return <h2>Hi, I am a Car!</h2>;
  }
}

function CarExample() {
  return <h2>Hi, I am a Car!</h2>;
}
```

* State:
* Hooks:
* Props:
* Virtual DOM:
* Element:
* Flux / Redux ('Ridux'):
* Scaffold out an application: 

