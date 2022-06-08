MVC Architecture - Angular.js uses MVC architecture in its approach to building web applications. MVC is a programming methodology which splits the application into three core components - model, view, controllers. These components combine form our applciation.

Model - Think of the model as data. Ex : JSON, data from database, etc

View - Used to display content & data to a user in a browser, HTML template that represents a view or state in your application, We can use 'expressions' to insert model data into views.

<html tag>{{data}}</html tag>

Controllers - Control the functionality of the views, allows data to pass between models and views - Performs the interaction between our models and our views. We can have different controllers for different areas in our application.

Flow example :

1. User clicks a 'show users' button in a view
2. The 'UserController' recognises the button click event and performs a function
3. The function communicates with the 'users' model and retrieves all the user data
4. The controller passes accessibility to this data to the view, which then displays it to the end user via expressions

MVC may be referred to MVW (Model View Whatever) in Angular. The underlying principle is the same. It is just a separation of concerns.

ng-app : directive, everything under (html elements) to be in angular architecture (controlled by angular)

Two way data binding: If we update model using view, it updates model in the code. If we update the model in the code, it updates the view.

ng-model: model directive can be associated with an input - whatever is written in the input will be stored in that model name. This can be later outputted to user using expressions.

Directives - Direct angular to do something for us - Tell angular to do something for us. They do not always have to be in the form of a html attribute, they may also be in the form of a html tag.
We can also create directives that extend html tags for us.

- I made these notes while doing the Angular course by Net Ninja on YouTube.
