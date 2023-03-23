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
