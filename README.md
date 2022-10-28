### Just some notes while I learn some stuff:
## What is MVC? (Model-View-Controller)
ASP.NET (Active Server Pages) MVC gives you a powerful, pattern-based way to build dynamic websites that enables a clean separation of concerns and that gives you full control over markup for enjoyable, agile development.
ASP.NET MVP includes many features that enable fast development for creating sophisticated applications that use the latest web standards.

Model = corresponds to the data that the app works with.
View = the UI of the app. Commonly called a web page.
<b>Models</b> are transferred to a <b>View</b> from a <b>Controller.</b>
<b>Controllers</b> act as an interface between the <b>Model</b> and the <b>View.</b> Listen to requests and interact with a DB using the <b>Model.</b>
Returns the <b>Model</b> to the <b>View.</b>

### What is Inheritance?
Mechanism where you can derive a class from another class so that they share a set of attributes and methods. For example...

- The base controller creates listeners for hangling requests and responses over HTTP
- Supports authorization and authentication
- Supports transmission of data to and from the server to the client with JSON
- Much more in framework already in place out of box

### What is a controller?
- Every controller class name must end with a word "Controller"

### What is a view?
- A view is an HTML template with embedded Razor markup
- Every view name must match the name of Controller Action
- e.g. if homepage controller has an action named Index, the View must be named Index.cshtml
  
### MVR Routing?
- Controller handle the request
- Action is the method in the Controller
- ID is not required to but used to query a database

Project Ideas:
- Blog Site
- Address Book or Loan Calculator
- Movie DB