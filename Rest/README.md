# Rest-Springboot
Creating a springboot Rest application that uses MongoDB using Java Techie tutorial. Link :https://www.youtube.com/watch?v=k5PeywcbVYc&ab_channel=JavaTechie

This springboot project uses the dependencies spring web, Lombok and spring data mongoDB.

The database used was a locally hosted mongoDB database with Database name: BookStore and Collection name: Book.

The spingboot application had the regular 3-layer structure of model, repository and resource/controller.

The API's implemented in the controller where:
  1. /addBook
  2. /findAllBooks
  3. /findAllBooks/{id}
  4. /delete/{id}

These where later tested using Postman.

The completion of this project taught me:
  1. How to setup a local mongoDB collection
  2. How to configure springboot application to access this mongoDB collection
  3. How to use postman to test the application
  4. Springboot makes it really easy to develop your app without worrying about the underlying complex technologies

In the future I want to develop more into REST applications and applications that use data from relational databases with multiple tables.


