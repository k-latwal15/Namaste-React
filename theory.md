1. What is Emmet?

Emmet is a free add-on for your text editor. It **allows you to type shortcuts that are then expanded into full pieces of code**. By using Emmet, developers type less, they save both on keystrokes and time.

Ex.  [div.group](http://div.group)  ⇒  <div class=”group”></div>

1. Difference between a Library and Framework?

library can be understood as collection of functions that can be used whenever required but framework is whole program itself which has the control flow and we provide our piece of code as plugin to the main program. framework consists all the necessary features built-in.  whereas library is used to perform a limited set of tasks. 

Ex. React and Nextjs ( react as library only handles the view part of application only ,for routing and app configuration we need to use react router ,redux to build a complete application. 

but in nextjs most of it is built in. we can build our application with minimum third party library usage).

1. What is CDN? Why do we use it?

content delivery network (CDN) refers to a geographically distributed group of servers which work together to provide fast delivery of Internet content.

A CDN allows for the quick transfer of assets needed for loading Internet content including HTML pages, javascript files, stylesheets, images, and videos.

1. Why is React known as React?

“And it's called React **because it reacts**
. It was developed by Facebook (a site that CONSTANTLY updates their data) to improve the user interface development and more effectively change (REACT to) what the user sees when they're doing things like mouse clicking, submitting and typing.”

1. What is crossorigin in script tag?

CORS stands for Cross-Origin Resource Sharing, and is a mechanism that allows resources on a web page to be requested from another domain outside their own domain. It defines a way of how a browser and server can interact to determine whether it is safe to allow the cross-origin request. CORS allows servers to specify who can access the assets on the server, among many other things.

1. What is diference between React and ReactDOM?

React: React is a javascript library, designed for building better user interfaces.

React-DOM: React-DOM is a complimentary library to React which glues React to the browser DOM

In a nutshell, Whenever we use **component, classes, elements**, etc. We’re using **React** and whenever we use methods like `render()` or `findDOMNode()` we’re using **React-DOM.**

1. What is difference between react.development.js and react.production.js files via CDN?

production build files are minified and resources are compressed.But in development file the is addition code react code to show warnings, errors to make development smooth.

1. What is async and defer?

 defer ⇒ if a script has defer tag it will be given least priority and loaded in paralled but executed at the end of html parsing.

async ⇒ in this case script will be loaded in parallel to other resources but after load its execution blocks the html parsing.