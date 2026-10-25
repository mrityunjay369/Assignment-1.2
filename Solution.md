

Aim

To set up the web development environment on a computer.

Procedure

1. Installed Visual Studio Code.
2. Installed the LTS version of Node.js.
3. Installed Live Server and Prettier extensions in VS Code.
4. Created a folder named "web-development-practice".
5. Created three files: "index.html", "style.css", and "script.js".
6. Wrote HTML, CSS, and JavaScript code in the respective files.
7. Opened "index.html" using Live Server.
8. Verified Node.js and npm installation using "node -v" and "npm -v" commands in the terminal.

index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Development Practice</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Welcome to Web Development!</h1>
    <p>My development environment is ready.</p>
    <button id="myButton">Click Me</button>
    <p id="message"></p>
    <script src="script.js"></script>
</body>
</html>

style.css

body {
    font-family: Arial, sans-serif;
    background-color: #f0f4f8;
    text-align: center;
    padding: 50px;
}

h1 {
    color: blue;
}

button {
    background-color: blue;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
}

script.js

const button = document.getElementById("myButton");
const message = document.getElementById("message");

button.addEventListener("click", function () {
    message.textContent = "JavaScript is working successfully!";
});

Verification Commands

node -v
npm -v

Result

The web development environment was set up successfully. The HTML page was opened in the browser using Live Server, and Node.js and npm installation were verified using terminal commands.

Submission

Attach screenshots of VS Code showing the project files, terminal showing Node.js and npm versions, and the running HTML page in the browser.
