###An intro to Webpack: what it is and how to use it
Webpack is a static module bundler. It goes through packages to create a dependency graph made of modules. Then it creates a new package with the smallest number of files for the html file to use.

###Webpack 5 Concepts
Webpack has a lot of configurable concepts. Entry, Output, Loaders, Plugins, Mode, and Browser Compatibility. Entry point is where webpack will start building the dependency graph, with the default being src/index.js. Output property is where the final product ends up and how to name these files. Loaders is a property that can allow webpack to work with different file type other than JS and JSON. Plugins can add functionality to webpack, like bundle optimization, asset management, and more. Mode can change built in optimizations for different environments. Browser compatibility is self explanatory.

###Rendering Elements
React elements are things you want to display to the screen. They are plain objects. updating objects requires creating and rendering a new react object, but react will only update the altered pieces of the element on the display.

###Hello World
Refresh on basic React.

###Introducing JSX
JSX is a syntax extension of javascript. It produces react elements. Concerns and components. This will be very cool for refactoring react apps.