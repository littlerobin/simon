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