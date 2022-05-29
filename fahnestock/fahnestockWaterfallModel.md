# Waterfall Model
![waterFallDiagram](fahnestock/img/waterfallModelDiagram.png)

### Interface and Database Schema Development
By defining the interface early both the frontend UI and backend database can be worked on asynchronously (if in a team larger than one.) Regardless this is a good starting place to design a system because it unveils the essential complexity of the system, and keeps the frontend and backend decoupled. Essential complexity is the stripped back complexity which exists in a real world domain, and the goal of most software projects is to represent this domain without adding unneeded complexity. Starting with an interface also helps enforce the dependency inversion principle which pushes for high and low level modules to depend on abstractions rather than each other. By helping decouple the frontend and backend the system becomes more maintainable and understandable since the scope of each module has just shrunk dramatically. In a real world project the interface stage would include speaking with domain experts and creating a model of the domain prior to starting the interface. Since the domain for this project is pretty simple the interface can also act as the domain model. Since it's unclear how much freedom is available tool wise the interfaces for this project will remain as classes. A majority of the classes were outlined in Assignment 1 with empty methods which will be filled in the database development stage. The main interface left to be designed is how dates and calendars will be handled, and stored in the database. 

### Database Development
Implement the classes/interfaces and their relationships. Put together the SQL for the main queries and commands in the sketched out methods in the classes.

### UI
Build the UI hopefully using some framework which uses components to combine styling and frontend logic into reusable components. Call the SQL queries and commands in the UI (most likely through the methods of the classes.)

### Testing
Write both component UI based tests and domain logic tests. For this project just poke around in the locally running project and check off the following:
* UI displaying properly
* Database tables match the current state of the written interfaces
* Queries and Commands reading and writing from the database properly

