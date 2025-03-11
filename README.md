# SpringBoot Social Network Project

- Circle CI build status:
[![CircleCI](https://circleci.com/gh/dmcheremisin/SpringBootSocialNetwork.svg?style=svg&circle-token=54d82edd98892db8d4e69740d9bee65e48242495)](https://circleci.com/gh/dmcheremisin/SpringBootSocialNetwork)

## Introduction
This project is a continuation of the previous one. The previous project was made with pure Servlets and JSP
 technologies [details here](https://github.com/dmcheremisin/SocialNetwork). I used the same
  template layout and created a new project using SpringBoot.

## Functionality
### Base
- Login / Logout
- Register
- View other users profiles
- Add and remove friends
- Accept and decline friends requests
- Update profile information
- Change password
- Search for other users
- View other users friends lists

### Admin
- Make other user admin
- Block user

## Technologies used 
### Stack:
- Java 11
- Spring: SpringBoot, MVC, Data JPA, Security, DevTools, Actuator
- Maven
- MongoDB
- Thymeleaf
- Javascript
- Html, CSS, Bootstrap

### Environment
- Heroku as CD tool
- Circle CI as CI tool
- Docker for containerization
 ### Required:
 - Java 11
 - Maven 
 boot app)
 
## Docker
This application is tested in Docker.  
I made 2 containers: mysql and social-network, and then linked them.  
Commands for images creation and containers startup may be found in the directory: [docker](https://github.com/dmcheremisin/SpringBootSocialNetwork/tree/master/docker)
