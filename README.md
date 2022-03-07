# Loan calculator

### Table of Contents
* [Description](#description)
* [Usage](#usage)
* [Learning Objectives](#objectives)
* [References](#references)

## Description
Loan calculator is a network application that calculates monthly payments based on amount borrowed, duration of repayment, and a fixed APR. This application was designed to generate web content dynamically based on the inputs from the user as well as allow users to calculate their monthly loan payments incrementally. 

| homepage | loan details |
| :------: | :----------: |
| ![form](/public/images/web1.jpg) | ![loan details](/public/images/web2.jpg) |

## Usage (Run from localhost)
1. Clone repositiory into desired directory location
2. Navigate to directory in the terminal
3. In the terminal:
	- Install packages with `npm install`
	- Create server with `node app.js`
4. Open any browser and type in `http://localhost:3000`
5. Use the application by Inputting and adjusting the inputs

## Learning Objectives
- Learning basic HTML and CSS syntax to to create templates
- Understanding how to design and implement a networked application
	- Modules:
		- `http` used to create server with `createServer()` method and `listen()` method to make it responsive to requests
		- `url` used to parse url and use query string as data in HTTP Request 
- Understanding the HTTP Request/Response cycle of a networked application
- Understanding Client and Server side workflows in an application
- Creating dynamic content with template engines
	- Modules:
		- `handlebars` used to create template for generating dynamic content 
- Understanding HTTP Methods and Static Assets
	- Modules:
		- `querystring` to use `querystring.parse()` method to access data in request body of `POST` method
		- `serve-static` used to handle requests for static files
- Using Routing engine to manage request handlers
	- Modules:
		- `router` & `finalhandler` used for routing and serve as middleware within our application

## References
- Project created for academic learning based on curriculum by Launch School