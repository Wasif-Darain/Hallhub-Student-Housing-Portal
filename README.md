Hallhub Project — Installation Guide

Prerequisites

Node.js must be installed (LTS version). Verify installation by opening Command Prompt : node -v npm -v

VS Code (recommended) with Live Server extension installed. Steps i. After Extracting the zip folder, go to hallhub-backend ii. Open terminal from that folder, make sure server.js in the same directory where the terminal is opened.

Run: npm install This will read package.json and install all required libraries into node_modules/.

In the same terminal, run: node server.js If everything is correct, a message should be seen like: Server is running on port 3000

    Open browser and go to: http://localhost:3000 
If you want to open static files like home.html instead of running the Node.js backend: Open the project in VS Code.

    Right-click home.html → Open with Live Server. 

   The page will open at something like 
http://127.0.0.1:5500/home.html.

To stop the Node.js server, press CTRL + C in the terminal.
Example login for Student: User id: 202314401 Pass: abcdef Login for Admin: User id: admin@ Password: pass@
