
     ,-----.,--.                  ,--. ,---.   ,--.,------.  ,------.
    '  .--./|  | ,---. ,--.,--. ,-|  || o   \  |  ||  .-.  \ |  .---'
    |  |    |  || .-. ||  ||  |' .-. |`..'  |  |  ||  |  \  :|  `--, 
    '  '--'\|  |' '-' ''  ''  '\ `-' | .'  /   |  ||  '--'  /|  `---.
     `-----'`--' `---'  `----'  `---'  `--'    `--'`-------' `------'
    ----------------------------------------------------------------- 


Welcome to this MEAN (Angular.js, Node.js) project built using Cloud9 IDE!

This Project is meant to Visualize the commit Propagation in the super-repository of Linux (Linus Torvalds) in 2012.

## Client code
For now, almost all the client side code is in `index.html` file. It has the JS and the d3 Library implementation code 
as well as the front-end stuff in AngularJS.
Since it's a SPA(Single Page Application), the server just loads this file.

## Running the server

1) Open `server.js` and start the app by clicking on the "Run" button in the top menu.

2) Alternatively you can launch the app from the Terminal:

    $ node server.js

Once the server is running, open the project in the shape of 'https://myproject-gauravsinghthakur.c9users.io/#/'.
Search for a Commit ID (Merge) in the linux repo and click to open the visualization to view the commit propagation
through several repositories for that merge!

