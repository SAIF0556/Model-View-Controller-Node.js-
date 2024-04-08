![image](https://github.com/SAIF0556/Model-View-Controller-Node.js-/assets/83172463/de21ed11-562e-4829-880c-40ee914d11d7)# Model-View-Controller-Node.js-
MVC (Model-View-Controller) is a pattern in software design commonly used to implement user interfaces, data, and controlling logic. It emphasizes a separation between the software's business logic and display. 

The Model
The model defines what data the app should contain. If the state of this data changes, then the model will usually notify the view (so the display can change as needed) and sometimes the controller (if different logic is needed to control the updated view).
Going back to our shopping list app, the model would specify what data the list items should contain — item, price, etc. — and what list items are already present.

The View
The view defines how the app's data should be displayed.
In our shopping list app, the view would define how the list is presented to the user, and receive the data to display from the model.

The Controller
The controller contains logic that updates the model and/or view in response to input from the users of the app.
So for example, our shopping list could have input forms and buttons that allow us to add or delete items.

