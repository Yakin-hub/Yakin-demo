ViewBag: A dynamic object used to pass data from the controller to the view. It is available only for the current request.
ViewData: A dictionary object that passes data between the controller and view. It also only persists for the current request.
TempData: A dictionary that can store data across requests. It is used when data needs to persist for one redirect or between requests (e.g., for flash messages). TempData is automatically cleared after the data is read.



Routing: Map the URL to a controller and action.
Controller Initialization: Create an instance of the controller.
Action Filters: Execute any action filters before the action method is invoked.
Executing the Action: Execute the controller action.
Result Filters: Execute any result filters before the view is rendered.
View Rendering: Render the view and generate the HTML response.
Response Sending: Send the response to the browser.
End Request: Perform any cleanup tasks after the request is completed.


What is Model Binding in ASP.NET MVC?
Answer: Model binding in ASP.NET MVC maps incoming HTTP request data (like form values or query strings) to action method parameters or model properties automatically. It allows easy extraction of data from requests into strongly-typed objects, reducing the need for manual parsing.
