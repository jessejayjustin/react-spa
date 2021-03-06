A simple model of React Single Page Application

![](https://github.com/jessejayjustin/react-spa/blob/master/public/images/react_spa.png)

## Getting Started

install dependencies

```
npm install
```

Run app in development mode.
Open http://127.0.0.1:3000 to view it in the browser.

``` 
npm run client (Hot Reload Dev Environment)
```

start dev server

```
npm run server
```

Launch test runner in interactive watch mode.

```
npm test
```

## General Flow

The flow goes something like this:

  1. Before the initial rendering occurs, the application dispatches an action creator which triggers a GET to the server, the server returns a data 

  2. The action creator parses the server response and returns Redux actions accordingly

  3. Success actions trigger an update of the application state, passing along any decoded data from the payload

  4. The connected component receives the new state as props renders its child component and passes the props down to it Before mounting, the child use the data it received from its parent wrapper
	
## Built With

* [React](https://reactjs.org/docs/getting-started.html) - The web framework used.
* [Redux](https://redux.js.org/introduction/getting-started) - A framework for application state management.
* [Webpack](https://webpack.js.org/) - Open-source JavaScript module bundler. 
* [Sass](https://sass-lang.com/) - The most mature, stable, and powerful professional grade CSS extension language in the world.
* [Bootstrap](https://getbootstrap.com/docs/4.3/getting-started/introduction/) - Open source toolkit for developing with HTML, CSS, and JS.
* [JSON Server](https://github.com/typicode/json-server) - For front-end developers who need a quick back-end for prototyping and mocking.
* [Jest](https://github.com/facebook/jest) - A comprehensive JavaScript testing solution.
* [Enzyme](https://github.com/airbnb/enzyme) - A JavaScript Testing utility for React. 

## Author

* **Jesse Jay** - *Initial work* - [jessejayjustin](https://github.com/jessejayjustin)
