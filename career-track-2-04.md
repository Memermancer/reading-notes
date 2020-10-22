## Reading: Class 29

### MVC
Model-View-Controller is a software development pattern traditionally used to develop GUIs but now has become popular for building web applications. The purpose is to separate internal logic and information from what is displayed to the user. The model is responsible for managing the data of the application. It receives user input from the controller. The view means presentation of the model in a particular format. The controller responds to the user input and performs interactions on the data model objects. The controller receives the input, optionally validates it and then passes the input to the model.

### Architecting Single Page Applications
Clear architecture is important for building web applications and for working with a team. Four layers of a single page application are the view, the application services, the store, and the domain. Each has its own purpose. View is a representation of the state. The domain describes the state and holds the business logic. The store holds the state. The application services layer interprets state and orchestrates external operations.

### A Model View Controller Pattern for React
React changed a lot recently with the introduction of hooks. React can now handle complex state management without using other tools. It also made it more obvious how important it is the keep components modular and of limited scope. MVC is a good way to keep these limits in mind while building applications. Separating presentation from domain is the main purpose, which makes code easier to maintain and more secure.

### Reconciliation
React provides a declarative API so that you don’t have to worry about exactly what changes on every update. React creates a tree of elements, then when state updates react needs to make a new tree of elements. It is expensive to re create that tree each time. So react reconciles the two trees and changes the fewest number of things each time, mostly to save resources. The algorithm that does this works off of two assumptions: Two elements of different types will produce different trees and the developer can hint at which child elements may be stable across different renders with a key prop. 