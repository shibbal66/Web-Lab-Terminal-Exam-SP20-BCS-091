# Lab Terminal Exam SP20-BCS-091
 
Question # 2 
Created basic express app in index.js file using express()
Created Mongo schema model in models>Todos.js
  ..included title , description and boolean in schema
Created CRUD APIs in routes>todos.js
  .. using express Router to handle incoming HTTP requests
  ...POST API creates new To-Do item & stores the data in MongoDB
  ....PATCH and DELETE APIs expect id with the HTTP request
Enabled CORS support and added body parser to express to accept JSON from HTTP Req.
Connected Backend Mongo with mongoose library.
Created react app using reactjs
I have already did some work on CRUD app in semester project


Queston # 1

Declared React States for error message and isSubmitted
Created renderErrorMessage function that return JSX code for error message
Added JSX code for the HTML form with input type=”text”
    .. displayed error messages below every form input element
Created handleSubmit() function that accesses event object of form
    ..Assigned handleSubmit() function to onSubmit property of form, thehandleSubmit() is triggered when button(submit) is clicked
Validated form input with user details

First it will find user details by matching usernames.
     ..If a match is not found then add it will show error message “invalid username“
     ...else validate the password, show the error message “invalid password” if validation fails
If all the submitted data is true, it will setIsSubmitted(true)
I tried to render input data of form using render method
but got error at this
Overall my form is working I also did validation and authorization.
render() { console.log(this.state.formData); return(...); }



  
