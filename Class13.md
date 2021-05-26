# CRUD

In your own words, describe what each group of status code represents:
100’s = **Informational letting the user know that a header was recieved and it will try to comply withwhat was sent by the user.**
200’s = **Success but this doesn't mean it will render anythign it just means that the information is valid.**
300’s = **Redirection the user may not get information because there resource is no longer valid in the current location.**
400’s = **Client errors which are invalid request**
500’s = **Sever erros due to the server being overwhelmed**
What is a status code 202? **Accepted**
What is a status code 308?**Permanent Redirect**
What code would you use if an update didn’t return data to a client? **204 No Content**
What code would you use if a resource used to exist but no longer does?**410 Gone**
What is the ‘Forbidden’ status code?**The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.**


Why do we need to pull our MongoDB database string out of our server and put it into our .env?
What is middleware? **Additional software that allows capabilites to the application beyod wht the OS can provide**
What does app.use(express.json()) do? **Takes in incoming request objects**
What does the /:id mean in a route?
What is the difference beween PUT and PATCH?**Put uses URI to modify, Patch is a set of instructions**
How do you make a defalut value in a schema?
What does a 500 error status code mean?**It is an internal server error**
What is the difference between a status 200 and a status 201?**200 is when information was recieved and presents the data. 201 is when the user has creating information on the server.**