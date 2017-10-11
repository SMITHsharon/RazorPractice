# RazorPractice
==============
## Set Up
**Scaffold your application in Visual Studio:**
 1. File > New > Project (ctrl + shift + n)
 2. Select Templates > Visual C# > Web > ASP.NET Web Application (.NET Framework)
 3. Name it RazorPractice
 4. Choose the MVC option and click Ok (initializing an empty git repo is a handy option here, too)
 
**In the Index.cshtml in your Views/Home/ folder** (correlates to the Home Controller):

1. Make a list of names (List<string>) in Razor code
2. Loop through the names in an unordered list on your page using Razor
3. Use a multi-line razor statement to make two variables (string UserName and string Greeting) and set the values to whatever you want.
4. Use your username and greeting variables in your html to say hello to your user 
5. Use an if statement to print "TGIF" on the page if it's Friday
7. Create a C# model in your Models folder for an object (think Song, Person, Order, Car, etc.)
8. Make a form to create an instance of your model (a song, a person, an order, a car, etc.) using the Razor @Html form, input, and other extensions (not standard HTML)
9. In the controller, make an action that accepts the POST request from the form you create and use the debugger to verify your form is submitting correctly.
[FormExtensions](https://msdn.microsoft.com/en-us/library/system.web.mvc.html.formextensions(v=vs.118).aspx),  [InputExtensions](https://msdn.microsoft.com/en-us/library/system.web.mvc.html.inputextensions(v=vs.118).aspx), and others! 
