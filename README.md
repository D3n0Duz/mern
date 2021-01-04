[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<p align="center">
  <a href="https://github.com/D3n0Duz/mern">
    <img src="https://blog.hyperiondev.com/wp-content/uploads/2018/09/Blog-Article-MERN-Stack.jpg" alt="Logo" >
  </a>

  <h3 align="center">MERN full-stack development</h3>

  <p align="center">
    This is a reference to learn MERN the fastest way possible.
    <br />
    <br />
    <a href="https://github.com/D3n0Duz/mern/issues">Report an issue</a>
  </p>
</p>


## Table of contents

   * [What is MERN Stack](#what-is-mern-stack)
        * [M for MongoDB](#m-for-mongodb)
            * [Examples of MongoDB usage](#examples-of-mongodb-usage)
        * [E for Express](#e-for-express)
        * [R for ReactJS](#r-for-reactjs)
        * [N for NodeJS](#n-for-nodejs)
   * [Overview](#overview)
        * [Front end](#front-end)
        * [Back end](#back-end)
   * [How it works together](#how-it-works-together) 
        * [REST APIs](#rest-apis)
        * [HTTP protocol](#http-protocol)


## What is MERN Stack
MERN Stack is a Javascript Stack that is used for **easier and faster deployment of full-stack web applications**. MERN Stack comprises of 4 technologies namely: MongoDB, Express, React and Node.js. It is designed to make the development process smoother and easier.

#### M for MongoDB
MongoDB is a cross-platform document-oriented NoSQL database program. Let's think about MongoDB like a **storage where we create, read, update or delete data** from. 

<p align="center">
    <img src="https://miro.medium.com/max/520/1*CbaCCU7Su4oOe4bhfxuVuw.png" alt="Logo" >
</p>

###### Examples of MongoDB usage

1. When we post a comment on Facebook, Facebook will create the data on its database that is MongoDB

2. When we open Facebook homefeed, Facebook will read all the comments data on its database that is MongoDB

3. If we decide to edit a comment on Facebook, Facebook will update the data on its database that is MongoDB

4. If we decide to delete a comment on Facebook, Facebook will delete the data on its database that is MongoDB

#### E for Express
Express is a **back end server framework for NodeJS** that we will import as a dependency in our project to run our web application on it.

#### R for ReactJS
ReactJS is a **front end framework language** that we will use in our project to build our user interface.

#### N for NodeJS
Node.js is a **back end language** that we will use in our project to have a server that handles requests and responses.

## Overview
<p align="center">
    <img src="https://www.educative.io/api/edpresso/shot/5266982947520512/image/6392882854363136" alt="Logo" >
</p>

#### Front end
The front end is principaly the visual user interface that a user sees when accessing the website. With client-side rendering (front end), the rendering of the content happens in the users computer instead of the remote web server using the de facto language of the web, JavaScript. 

For the front end, we will use the ReactJS framework.

#### Back end
While front-end development is about making sites and web applications render on the client-side, back-end development is all about making these apps render server-side. But it's a bit more involved than that. While the previous statement holds true, back-end developers also create services that process business logic and access other resources such as databases, file servers, cloud services and more.

For the back end we will use NodeJS with the Express framework to create endpoints.

## How it works together
Now that we know what is a front end and a back end, we must glue them together to make everything work from end-to-end.

The flow is quite simple and it's like humans, it's all about communication.

1. The front end has an action (for exemple: Alice that posts a new Tweet)
2. Once the action is done (for exemple: Alice click on the `post` button), the front end contacts the back ends endpoint with the data (of the post)
3. The back-end validates the data and since it's a new entry it creates the data inside the database
4. Once the data created in the database, the back end responds to the front end that everything is ok

Now, lets see how the communication between front end and backend works with more details.

#### REST APIs
For the front end to contact the back end, it needs to talk with something and this something is REST APIs. The back end will have multiple endpoints/APIs available that the front end can call.

Basicaly, the back end is only here to host endpoints that the front end will consume. For that, it needs to respect a certain protocol. This protocol is what we call the HTTP protocol.

<p align="center">
    <img src="https://i.redd.it/31njay53mr151.jpg" alt="Logo" >
</p>

#### HTTP protocol
The HTTP protocol is based on requests and response.

<p align="center">
    <img src="https://miro.medium.com/max/853/1*8-fT6K1o6nHiBRxKppcqOg.png" alt="Logo" >
</p>

###### Request
The HTTP Request is what the front end sends to the backend and it must contain

1. The HTTP method
2. The endpoint path
3. The host url of the back end to contact
4. A body if needed (we will see this in the back end README section)


<p align="center">
    <img src="https://mdn.mozillademos.org/files/13687/HTTP_Request.png" alt="Logo" >
</p>

The back end must provide endpoints to the front end for the specific HTTP method that does a specific task.

![image](https://user-images.githubusercontent.com/33992884/103501535-78f05800-4e1c-11eb-9beb-3851ff5ee8d0.png)


Here is a mapping of the HTTP methods and database CRUD

![image](https://user-images.githubusercontent.com/33992884/103501453-362e8000-4e1c-11eb-95f0-dc0b18446219.png)

###### Response
The HTTP Response is what the back end sends to the front end. It contains

1. The status code (https://httpstatusdogs.com/)
2. The content-type of the response (we will see this in the back end README section)
3. A body if needed (we will see this in the back end README section)

[contributors-shield]: https://img.shields.io/github/contributors/D3n0Duz/mern.svg?style=flat-square
[contributors-url]: https://github.com/D3n0Duz/mern/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/D3n0Duz/mern?style=flat-square
[forks-url]: https://github.com/D3n0Duz/mern/network/members
[stars-shield]: https://img.shields.io/github/stars/D3n0Duz/mern.svg?style=flat-square
[stars-url]: https://github.com/D3n0Duz/mern/stargazers
[issues-shield]: https://img.shields.io/github/issues/D3n0Duz/mern.svg?style=flat-square
[issues-url]: https://github.com/D3n0Duz/mern/issues
[license-shield]: https://img.shields.io/github/license/D3n0Duz/mern.svg?style=flat-square
[license-url]: https://github.com/D3n0Duz/mern/blob/main/LICENSE.txt