# react-tic-tac-toe-hooks
React Tic Tac Toe Game using Functional Components and Hooks
---------
## Install
Open you terminal and enter the following
```
$ git clone {url to the repo}
````
cd into the folder of the code and type
```
$ npm install
```
To run the React project enter the following in the terminal
```
$ npm start
```
----------
## Important functionality

### Helper.js
calculateWinner is used to check if ther is a winner, or three of the same symbols in a row
The funciton is provided with a list of all possible winning locations, or indexes, where a winning set of matching symbols are possible. 

### Board.js
The board is made up of map of squares.

### Square.js
Used to change the value within the square once clicked.

### Game.js
Where most of the functionality is located. 
Defines how to handle clicks, keeps track of game history, and checks if there is a winner. 
