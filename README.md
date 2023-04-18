# simon
simon startup assignment

table format in HTML:
<table>
  <thead>     //this represents the top row of a table, it has the headers for each column
    <tr>      //table row, starts a new row
      <th>HEADING</th>
    </tr>
  </thead>
  <tbody>     //starts the table body
    <tr>
      <td>DATA</td>
    </tr>
  </tbody>
</table>

.ico files are needed to make the small icon by the web address

header remained the same:
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Scores</title>
    <link rel="icon" href="favicon.ico" />
  </head>
  <body>
    <header>
      <h1>Simon<sup>&reg;</sup></h1>

      <nav>
        <menu>
          <li><a href="index.html">Home</a></li>
          <li><a href="play.html">Play</a></li>
          <li><a href="scores.html">Scores</a></li>
          <li><a href="about.html">About</a></li>
        </menu>
      </nav>

      <hr />
    </header>

Footer remained the same as well:
        <footer>
            <hr />
            <span class="text-reset">Author Name</span>
            <br />
            <a href="https://github.com/littlerobin/simon">GitHub</a>
        </footer>
        
    
Simon CSS code
    
Learned about selectors and declarations and rulesets
    
implementing bootstrap is a little tedious
dont forget to link html files to CSS files
dont forget to add bootstrap to html files to get it to actually work right...

CS 260

How the game logic works: By examining the code, you can see how the game logic is implemented, how the user's selection is processed, how the score is calculated.

How the DOM is manipulated: JavaScript is used to manipulate the Document Object Model (DOM), which is the representation of the HTML page in the browser. By looking at the code, you can see how the game elements are created, how they are updated, and how they are displayed on the page.

How user input is handled: The code will show how the game handles user input, including how it detects clicks on cards and how it responds to user actions

How variables and functions are used: The code will use variables and functions to store and manipulate data. By examining the code, you can see how these variables and functions are used to implement the game logic.

How the code is structured: The code will be organized into functions and modules to make it easier to read and maintain. By examining the code, you can see how the different parts of the game are structured and how they interact with each other.

How external libraries are used: The code may use external libraries, such as jQuery or Bootstrap, to simplify the development process or to add additional functionality to the game. By examining the code, you can see how these libraries are used and how they integrate with the rest of the code.

How the code is optimized: The code may be optimized to improve performance, such as using caching to reduce the amount of data that needs to be loaded or using asynchronous functions to avoid blocking the user interface. By examining the code, you can see how these optimization techniques are used to make the game run more smoothly.
    
Update for simon service:
    
URL - Stands for Uniform Resource Locator.
Used to locate and access resources on the web.
Consists of a protocol, domain name, and optional path and query parameters.

Ports - Used to identify specific processes or services running on a computer.
Range from 0 to 65535.
Some ports are reserved for specific services, such as port 80 for HTTP.

HTTP - Stands for Hypertext Transfer Protocol.
Used to transfer data over the web.
Uses a client-server model where the client sends requests to the server and the server responds with data.

SOP and CORS - SOP stands for Same-Origin Policy.
CORS stands for Cross-Origin Resource Sharing.
Both are security mechanisms that restrict how web pages can interact with resources from different origins.

Fetch - A modern API for making HTTP requests in JavaScript.
Replaces the older XMLHttpRequest (XHR) API.
Returns Promises that can be handled asynchronously.

Service design - The process of designing and delivering services that meet the needs of customers.
Involves understanding customer needs, designing service offerings, and managing service delivery.

Node.js - An open-source, cross-platform JavaScript runtime environment.
Allows developers to run JavaScript code outside of a web browser.
Used for building server-side applications and command-line tools.

Express - A popular Node.js web application framework.
Provides a simple and flexible API for building web applications and APIs.
Includes features such as routing, middleware, and template rendering.

Debugging Node.js - Involves using tools such as the Node.js debugger, console.log statements, and third-party debugging tools.
Can be challenging due to the asynchronous nature of Node.js applications.
Best practices include using good logging practices and writing test cases.

Service daemons PM2 - A process manager for Node.js applications.
Can be used to start, stop, and monitor Node.js processes.
Provides features such as process clustering and automatic restarts.

UI testing - Involves testing the user interface of a web application.
Can be automated using tools such as Selenium, Puppeteer, or Cypress.
Helps ensure that the application is functional and user-friendly.

Endpoint testing - Involves testing the API endpoints of a web application.
Can be automated using tools such as Postman or Newman.
Helps ensure that the API is functioning correctly and returning the expected results.

update for simon-login

Authorization services:
Used to control access to resources based on user permissions.
Typically involve user authentication and authorization.
Can be implemented using various protocols and standards, such as OAuth and JWT.

Endpoint design:
Involves designing the endpoints of a web API to meet the needs of the application.
Should be designed to be consistent, intuitive, and easy to use.
Can be documented using tools such as OpenAPI or Swagger.

Web service using Express:
Express is a popular Node.js web framework.
Can be used to build web services and APIs.
Provides features such as routing, middleware, and error handling.

Handling requests:
Involves receiving and processing requests from clients.
Requests can be handled using middleware functions in Express.
Requests should be validated and processed securely to prevent security vulnerabilities.

Using a Mongo database:
MongoDB is a popular NoSQL database.
Can be used with Node.js applications.
Provides features such as schemaless data storage and automatic scaling.

Generating authentication tokens:
Authentication tokens are used to authenticate users and control access to resources.
Can be generated using various algorithms, such as HMAC or RSA.
Tokens can be signed and encrypted for security.

Securing passwords:
Passwords should be stored securely using techniques such as hashing and salting.
Can be implemented using libraries such as bcrypt or argon2.
Should be validated and enforced using strong password policies.

Passing authentication tokens:
Authentication tokens should be passed securely between the client and server.
Can be passed in the headers or in the request body.
Tokens should be validated and verified on the server side.

Login endpoint:
The login endpoint is used to authenticate users and generate authentication tokens.
Should be designed to be secure and user-friendly.
Can be implemented using various authentication protocols, such as OAuth or JWT.

Securing endpoints:
Endpoints should be secured to prevent unauthorized access.
Can be secured using techniques such as authentication and authorization.
Should be tested and validated using tools such as Postman or Newman.

Update for Simon-webSocket
    
Debugging WebSocket

WebSocket communication can be debugged on both the client and server sides using VS Code and Chrome debugger respectively
Chrome debugger has built-in support for debugging WebSocket communication
    
To debug the server side, create a directory named "testWebSocket" and follow the below steps:
    Run "npm init -y"
    Run "npm install ws"
    Create a file named "main.js" and paste the provided code in it
    Set breakpoints on the "ws.send" lines to inspect the executing code
    Press F5 to start debugging (may need to choose Node.js as the debugger for the first time)
    
To debug the client side:
    Open Chrome debugger by pressing F12
    Paste the provided code in the console window and execute it to immediately hit the server breakpoint
    Select the Network tab, then select the HTTP message generated by the client code execution
    Click the Messages tab to view the WebSocket messages
    Send a message to the server by executing "socket.send('I am listening')" in the console window, which will hit the second server breakpoint
    Explore and remove the breakpoints from the server to observe communication back and forth without stopping on breakpoints.

WebSocket Chat:

how to build a simple chat application using WebSockets in Node and the browser.
The chat client is an HTML page with an input for the user's name, an input for creating messages, and an element to display the messages that are sent and received.
The JavaScript code interacts with the DOM to create and display messages and manages the WebSocket connection to connect, send, and receive messages.
The DOM interaction code ensures that the chat controls are disabled if the user has not specified a name and provides a function to update the displayed messages by appending new messages to the chat-text element.
The sendMessage function is called when the user presses the enter key in the message input. It selects the text out of the new-msg element and the name out of the my-name element and sends that over the WebSocket. The value of the message element is then cleared so that it is ready for the next message.
The WebSocket connection code sets up the WebSocket to connect to the same location that the HTML page was loaded from and notifies the user that chat is ready to go by appending some text to the display using the appendMsg function.
When the WebSocket receives a message from a peer, it displays it using the appendMsg function. If the WebSocket closes for any reason, it also displays that to the user and disables the chat controls.
    
Chat server

The chat server is responsible for running the web service, serving up the client code, managing the WebSocket connections, and forwarding messages from the peers.
The web service is created using a simple Express application, and the client HTML, CSS, and JavaScript files are served up using the static middleware.
The WebSocket server is created using the WebSocketServer object from the ws library, and the HTTP connection and upgrade to WebSocket are handled manually by specifying the noServer option and handling the upgrade notification that occurs when a client requests the upgrade of the protocol from HTTP to WebSocket.
Messages are forwarded between peers using the connection, message, and close events. When a connection is established, an object representing the connection is inserted into a list of all connections from the chat peers. Then, when a message is received, the server loops through the peer connections and forwards it on to everyone except the peer who initiated the request. Finally, a connection is removed from the peer connection list when it is closed.
In order to keep connections alive, the WebSocket protocol supports the ability to send a ping message to see if the peer is still there and receive pong responses to indicate the affirmative. To implement this, the server sends out a ping every 10 seconds to each of its peer connections using setInterval. Connections that do not respond to the ping are terminated, while those that do respond are marked as alive. Any connection that remains in the not alive state will be cleaned up on the next pass.

Update for Simon DB
    
MongoDB Atlas:

MongoDB Atlas is a cloud-based database service offered by MongoDB, the leading NoSQL database provider.
It is a fully managed, global cloud database that enables developers to deploy, operate, and scale their MongoDB clusters with ease.
Atlas offers features such as automatic scaling, high availability, backup and recovery, and advanced security to help developers build highly available and scalable applications.
With Atlas, developers can choose from different cloud providers such as AWS, Google Cloud Platform, and Microsoft Azure, and deploy their MongoDB clusters in multiple regions around the world for optimal performance.
Data Clusters in MongoDB Atlas:

In MongoDB Atlas, data clusters are a group of servers that store and manage data for a MongoDB database.
Atlas provides different types of clusters, such as replica sets and sharded clusters, to meet the specific needs of an application.
Replica sets are used for high availability and consist of a primary node and one or more secondary nodes that replicate data from the primary node.
Sharded clusters are used for horizontal scaling and consist of multiple shards, each of which is a replica set.
Atlas also offers features such as automatic scaling, data tiering, and backup and recovery to help developers manage their data clusters with ease.
Developers can monitor their data clusters using Atlas's built-in monitoring and alerting features, and can also integrate with third-party tools such as New Relic and Datadog for more advanced monitoring and analysis.
    
Environment Variables:

Environment variables are dynamic values that can affect the behavior of a running process or application.
They are typically used to store configuration settings or other data that are required by an application at runtime.
Environment variables are set and managed by the operating system or runtime environment and can be accessed by any process or application running on the same system.
Environment variables are typically named in uppercase letters, with words separated by underscores (e.g. PATH, HOME, USER).
They can be accessed and modified using system-specific commands or programming languages such as Bash, PowerShell, Python, and Node.js.
Environment variables can be used to store sensitive data such as passwords or API keys, but it is recommended to use a secure mechanism such as a secrets manager or encrypted file for storing such data.
In cloud-based environments, environment variables can be set and managed using platform-specific tools such as AWS Parameter Store or Azure Key Vault.
Environment variables are commonly used in containerized environments such as Docker and Kubernetes to provide configuration settings to containerized applications.
Environment variables can also be used in local development environments to provide configuration settings for developers and to ensure consistency between development, testing, and production environments.

Update for Simon React

Converting an application from HTML/CSS/JavaScript to React steps:

1. Reorganize Simon:
Commit the current version in Git as the starting place for the conversion to React.
Create a template React application using create-react-app and move it into the Simon code repository.
Clean up the template code by uninstalling and removing unnecessary files.
Rename .js files to .jsx extension and update the favicon and manifest files for Simon.
2. Move template files to Simon:
Copy the generated files from the template-react directory to the simon repository directory.
Delete the template template-react directory.
3. Convert to React Bootstrap:
Refactor the code to use React Bootstrap components.
4. Populate App.jsx:
Add code to App.jsx to render the Simon game.
5. Create view components:
Refactor the code into smaller, reusable components.
6. Create the router:
Set up a router to handle different views of the game.
7. Convert to React components:
Further refactor the code to take advantage of React-specific functionality.
8. Set up to debug:
Configure the application for debugging.
9. Refactor play.jsx into simonGame.jsx, simonButton.jsx, and players.jsx:
Refactor the code into separate components for better organization.
10. Refactor components:
Refactor the components to create sub-components and take advantage of React-specific functionality.
service code is moved into a subdirectory named service
UI code is moved into the src directory
UI code is moved from the public directory to a temporary directory named old-public and then moved to the React componentized version in the src directory
old-public directory is deleted once all the code is moved over.

To convert to React Bootstrap:
start by installing the react-bootstrap package via npm
  This package contains React components that wrap around the Bootstrap CSS framework, making it easier to use and customize.

To install, run the following command:
npm install bootstrap react-bootstrap

import the Bootstrap CSS file in your components by adding the following line of code:
import 'bootstrap/dist/css/bootstrap.min.css';

Move the main CSS content into a separate file called app.css and import it into your App.jsx file like so:
import './app.css';

debugging a web service running under Node.js:

In production, the Node.js web service running on port 3000 serves up the Simon React application code when the browser requests index.html. The service pulls those files from the application's static HTML, CSS, and JavaScript files located in the public directory.

When running in debug mode on a development environment, two HTTP servers are needed. One for the Node.js web service to debug the service endpoints, and one for the React client HTTP debugger to develop and debug the React application code.

To configure the React debugger HTTP server to listen on port 3001, create a file named .env.local in the root of the project, and insert the following text: PORT=3001.

Modify the package.json file to include the field "proxy": "http://localhost:3000". 
This tells the React HTTP debugger to forward requests to port 3000, where the Node.js service is listening.

Change the front-end WebSocket initialization found in the gameNotifier.js constructor to explicitly use the service port (3000) instead of the React HTTP debugger port (3001). To do this, use the dynamically injected process environment variable that is set when webpack creates the application bundle.

This configuration is necessary to debug the entire application in a development environment.
