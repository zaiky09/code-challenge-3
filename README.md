# code-challenge-3

# Description 

Flatdango, Flatiron movie theater is open! Aim is to build an
application, Flatdango! allowing a user to purchase movie tickets from the Flatiron
theater.

A user, should be able to:

1. See the first movie's details, (i.e. its poster, title, runtime,
   showtime, and available tickets) when the page loads. User should also be able to see the number of
   available tickets.
 
2. See a menu of all movies on the left side of the page when the page loads.

3. Buy a ticket for a movie. After clicking the "Buy Ticket" button and should not
   be able to buy a ticket if the showing is sold out.
 
 # Setup
 
    ## Getting Started
To use the content on this repository, ensure you have the following:

- A computer that runs on either of the following; (Windows 7+, Linux, Mac OS)
- nodejs 9.0+


## Installation

To use this repository on your machine requires some simple steps

### Option One

- Open a terminal / command line interface on your computer
- Navigate to a folder you would like to clone the repository

        using cd "folder name"
        
- Clone the repository by using the following:

        git clone git@github.com:zaiky09/code-challenge-3.git

- Be patient as it creates a copy on your local machine for you.
- Change directory to the repo folder:

        cd code-challenge-3
  

- Open it in ``Visual Studio Code``

        code .

### Option Two

- On the top right corner of this page there is a button labelled ``Fork``.
- Click on that button to fork the repository to your own account.
- Take on the process in ``Option One`` above.
- Remember to replace your username when cloning.

        git clone https://github.com/your-username-here/code-challenge-3.git



# Running the application

To run the application, you can use the following steps 

- Run this command to get the backend started:

          json-server --watch db.json

Test your server by visiting this route in the browser:

          http://localhost:3000/films

Then, open the index.html file on your browser to run the application.


- Install required dependencies from npm

      npm install
      
- Run the application

      npm node.index.js


# Author & Licence

Author : Zamil Mozamil Sheikh
Licence : MIT
