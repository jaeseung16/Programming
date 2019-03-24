## Lesson 3

Consider the technologies you used to create the activities microservice:

Swift Packages: Kitura, Swift-MySQL
Database: MySQL
Other Tooling: Make, Docker, Swagger, Git
This is quite a list! Congrats on using each of them! Before you wrap up the lesson, here are a few other technologies you may want to use as you continue to build Swift microservices:

[Swift Server Generator](https://www.kitura.io/en/starter/generator.html)
A set of command line tools that can generate a Kitura server from a Swagger specification or by completing a guided question-and-answer wizard. These tools specialize in generating CRUD-based servers.

[Swift Kuery: MySQL Plugin](https://github.com/IBM-Swift/SwiftKueryMySQL)
A Swift package (plug-in) based on Swift Kuery that provides a type-safe MySQL client. There are similar packages for Postgres and SQLite.

[Bluemix CLI](https://console.bluemix.net/docs/cli/idt/index.html#developercli)
The Bluemix CLI provides extensions for automating Docker commands and constructing a development environment for server-side Swift projects. It also makes possible the use of Xcode to construct your server-side Swift project while simultaneously using Docker under the hood.