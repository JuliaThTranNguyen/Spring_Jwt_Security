# :book: Spring_Jwt_Security :coffee:
----------------------------------------------------------
## This repository is a following course from [Youtube](https://www.youtube.com/watch?v=KxqlJblhzfI&t=1578s)

<br/>

## Description :bulb:

In this video, you'll learn how to implement JWT authentication and authorization in a Spring Boot 3.0 application using Spring Security 6 and a Postgres database to store user credentials. 

You'll see how easy it is to secure your application and protect your endpoints using JSON Web Tokens. We'll start by setting up a Postgres database and creating a user table to store our credentials. 

Then, we'll configure Spring Security to use JWT and define some security rules for our application. Finally, we'll test our setup by building a simple API and using Postman to send authenticated requests. 

Whether you're a beginner or an experienced developer, this tutorial will give you the tools you need to secure your Spring Boot application with JWT authentication and authorization.

----------------------------------------------------------

## IDE & Tools I use for coding 💻   🎒
===========================================
- ITerm
- VsCode
- GoLand
- IntelliJ Ultimate
- Sublime


<br/><br/>
## BackEnd Architechture:
===========================================

![Screenshot from 2023-03-19 16-57-58](https://user-images.githubusercontent.com/49017322/226323291-64c0778f-4563-4f6f-84e2-a2f269f41ccb.png)

## What will we need to generate this Springboot application:

![Screenshot from 2023-03-20 13-14-04](https://user-images.githubusercontent.com/49017322/226323808-58255e5d-a3f9-40c5-8997-7cc6682c5837.png)

<br/><br/>

## Spring boot dependencies explanation:
### Lombok

- Lombok is a Java library that provides a set of annotations to help reduce boilerplate code in Java classes. It can be used in a Spring Boot application to reduce the amount of code needed for getter and setter methods, constructors, and other common methods.

### Spring Security

- Spring Security is a framework used for authentication, authorization, and other security features in Spring applications. It provides a set of security filters and components that can be used to secure web APIs, web pages, and other resources in a Spring application. Spring Security can be used with a variety of authentication and authorization mechanisms, including JWT, OAuth, and basic authentication.

## What is JWT (JSON Web Token)?

- WT (JSON Web Token) is a technology used for authentication and authorization in web applications. In a Spring Web application, JWT can be used to secure the endpoints exposed by a web API.
    
- When a user logs in to the application, a JWT token is generated and sent to the client. The client then includes this token in every subsequent request to the server. The server verifies the token to authenticate and authorize the request.

<br/><br/>

## Proof of Complement:
===========================================

### Table creation:

![Screenshot from 2023-03-20 13-07-40](https://user-images.githubusercontent.com/49017322/226322900-608034b0-57d1-4c14-bff6-63f0a414c9e8.png)

### [Where to get a Jwt - online token ?](https://www.allkeysgenerator.com/Random/Security-Encryption-Key-Generator.aspx)

![Screenshot from 2023-03-20 11-13-29](https://user-images.githubusercontent.com/49017322/226323095-03907590-bbcd-45a3-b86d-4dd79cc97cd6.png)

### Testing HTTP requests with Docker:

![Screenshot from 2023-03-20 13-21-08](https://user-images.githubusercontent.com/49017322/226328734-66d3f678-0ec6-4431-ae94-69352797dc26.png)

### [Encoded the auto generated jwt-token which received during the testing phase:](https://jwt.io/)

![Screenshot from 2023-03-20 13-28-25](https://user-images.githubusercontent.com/49017322/226326741-2529d015-dd76-4c02-bdc7-3d466daf64bc.png)

