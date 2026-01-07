#  Express Lab – Creating An Express Server (JavaScript)

##  Overview
In this lab, you will learn how to set up a basic Express server using Node.js and serve static HTML pages. This foundational lab helps you understand routing, middleware, and project structure for web applications.

##  Workplace Context
Express is widely used in web development to build backend APIs and serve web pages. Understanding Express basics is essential for full-stack development, especially when working with Node.js, React, or other frontend frameworks.

##  Learning Objectives
By the end of this lab, you should be able to:

* Set up a Node.js project with Express.
* Serve static HTML files using Express routes.
* Understand middleware (express.static) for serving assets.
* Configure your server to listen on a specific port.
* Organize your project files for clarity and scalability.

##  Description

This lab focuses on:

* Installing and configuring Express in a Node.js project.
* Creating GET routes for / (home) and /contact.
* Serving HTML pages from a public directory.
* Understanding how Express handles static files and routing order.

##  Resources

* Express Official Documentation - https://expressjs.com
* Node.js Official Documentation - https://nodejs.org/docs/latest/api/
* Path Module Documentation - https://nodejs.org/api/path.html

##  Getting Started

##  Requirements

*  Node.js v24+
*  npm
*  Git
*  A code editor (VS Code recommended)

##  OS Compatibility

This lab works on:

*  Windows
*  macOS
*  Linux

##  Installation

1. Clone the repository:

git clone [<repository-url>](https://github.com/KaeTheDev/Daily-Grind-Server.git)

2. Navigate into the project folder:

cd daily-grind-server

##  Setup

1. Install dependencies:

npm install

2. Run the project:

node server.js

##  Project Structure
daily-grind-server/
├── server.js          # Main Express server
├── package.json       # Project metadata & dependencies
├── package-lock.json
├── node_modules/      # Installed npm packages
├── public/            # Static HTML pages
│   ├── index.html
│   └── contact.html
└── .gitignore         # Files/folders ignored by Git