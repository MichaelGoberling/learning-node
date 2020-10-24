# 1 Introduction

## Summary

In this section, we will be installing Node.js on the computer, understanding its role theoretically as a technology solution, and implementing some simple examples to get us started actually using Node.js.

## Notes

### Installing Node.js and Creating our First App

Installing Node.js on Windows is as easy as running an executable obtained from the Node website.

There are two ways to run Node.js code. First, you can simply run `node` to gain access to an interpretator that will allow you to submit statements that Node.js will evaluate and return values for. Alternatively, you can run `node <filename>` to run all the code contained in a file, and Node.js will evaluate that code.

`console.log()` allows you to print values to the screen.

There is a library called `fs` which enables interaction with the host operating system. To write a file to the system, you can use the `writeFileSync(filename, valuesToWrite)` function.

### Understanding the Role and Usage of Node.js

Node.js runs as a server side runtime for things like handling authentication, saving user data, and more. Ultimately, Node.js is used for event IO like HTTP requests and responses and it can be used to host RESTful API's.

It is also a perfect candidate for writing build tools with as it has access to the host filesystem.

Some alternatives to Node.js are Python (Django, Flask), PHP with Laravel (?) and Ruby on Rails or ASP.NET.

A great benefit of using Node.js is that when you are writing a frontend using JavaScript, you can use the same language in the backend to implement your business logic, authentication, or whatever. This also means that if you have some sort of shared components between the frontend and backend, you can avoid repeating yourself and stay DRY.

### Course Outline

This course is heavily focused on using Node.js to develop web servers. I am going to attempt to remember everything this course will cover:

- Simple static website hosting
- User authentication
- Validating user input
- Handling errors
- MVC
- Interfacing with MySQL
- Interfacing with MongoDB
- Hosting a REST API with Express.js
- Using async/await
- Using GraphQL
- Using Stripe.js to handle payments
- Using TypeScript
- Trying out Deno

### How to Get The Most Out of The Course

- Watch the videos
- Code along with the course at your own pace
- Ask questions in the Q&A
- Answer questions in the Q&A

My personal approach will be to watch videos all the way through and then attempt to perform the coding exercise as opposed to attempting to choppily implement alongside the presenter.

### Working with REPL vs. Using Files

### Using the Attached Source Code

## Conclusion
