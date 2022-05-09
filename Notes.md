DOM Scripting

-JS directly manipulates the DOM
-The browser performs a series of operations to reflect changes
-Layout, reflow, and repaint
-Every change triggers these steps

React Virtual DOM
-React has a virtual DOM it keeps in memory that it manipulates
-any number of edits in React will be made to the Virtual DOM
-Ract will reconcile the differences into the diff pool
-Determines minimal amount of DOM updates to perform
-Diffing algorithm compares the rendered DOM tree with a modified DOM tree
-In this process React minimizes potential read write operations to the DOM and the changes take effect immediately

### Start Using React Right Away

-Two ways to run React: locally or in the browser
-The browser option bypasses any setup and configuration involved in running a React application
-In browser tools (code editors) provide a virtual environment to jump into React to learn and play

### Local React Dev Environment Setup with create-react-app

npx is the package runner
npm is the package manager
