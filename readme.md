# Read Text File

This is a simple web application that reads and displays the content of a text file in a formatted way. It uses HTML, CSS and JavaScript to create a user interface and fetch API to get the file content. It also updates the content automatically every 1 second.

## Step-by-step Guide

To run this web application on your computer, you need to follow these steps:

1. Download or clone this repository to your local machine.
2. Open the info.txt file in a text editor and edit it according to your preferences. The text file should have the following format:

leelamove:

e2e4

eval:

0.00

line 1:

e2e4 e7e5 g1f3 g8f6 d2d4 f6e4 f1d3 d7d5 f3e5 b8d7

line 2:

d2d4 g8f6 c2c4 c7c6 g1f3 d7d5

line 3:

g1f3 d7d5 d2d4 g8f6 c2c4 d5c4 e2e3 a7a6 f1c4

The leelamove value is the move that you want to display. It should be four characters long, representing the from and to squares in algebraic notation.

The eval value is the evaluation of the move. It should be a number, representing the advantage or disadvantage of the move in pawns.

The line 1, line 2 and line 3 values are the possible continuations after the move. They should be a series of moves in algebraic notation, separated by spaces.

You can change any of these values as you like, but make sure to follow the format and syntax.

3. Save and close the info.txt file.
4. Open the index.html file in a web browser. You should see something like this:

Move from Where: e2

Move to Where: e4

Evaluation: 0.00

Line 1: e2e4 e7e5 g1f3 g8f6 d2d4 f6e4 f1d3 d7d5 f3e5 b8d7

Line 2: d2d4 g8f6 c2c4 c7c6 g1f3 d7d5

Line 3: g1f3 d7d5 d2d4 g8f6 c2c4 d5c4 e2e3 a7a6 f1c4

You can see the move information displayed in a user-friendly way. The web application will also update the content every 1 second, so if you change the text file and save it, you will see the changes reflected on the web page.
