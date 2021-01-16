## Numpy Arrays


Submission pull request: https://github.com/kimmyd70/chess_board/pull/1

__________
#### Developer: Kim Damalas
#### Created: 16 January 2020
#### Version 1.0 
#### Class: seattle-py-401n2
#### Lab: 11
___________
## Description
___________

Build a chessboard with arrays and pixe lart
____________
## Feature Tasks and Requirements
___________

1. Your job is to render out chess boards with red and blue queens on them.

2. We’re keeping it really basic here so the only pieces are queens and each queen is represented by a blue or red square.

3. Chess board is an 8 by 8 grid of alternating black and white squares. The queens are red and blue squares.

4. Each board will have one red and one blue queen at different coordinates. In addition to displaying the board you’ll need to identify if the queens are “under attack” based on their coordinates.

5. Define a `ChessBoard` class - should contain an 8x8 grid - Each cell in grid should have a color represented in RGB format. - black = (0,0,0) - white = (1,1,1) - blue = (0,1,1) - red = (1,.2,0)

- should have `add_red` method that accepts a row and column as input which colors corresponding cell.

- should have `add_blue` method that accepts a row and column as input which colors corresponding cell.

- should have `render` method that displays the chess board on screen with red and blue shown in correct locations

- should have `is_under_attack` method that return boolean if red is under attack by a blue piece horizontally, vertically or diagonally
______________

## Configuration and Technologies
__________

The user must have Python and all associated dependencies installed.  Poetry was used to create the project and the program is run by typing  `pythonic_garage_band.py` in the command line
___________
## Changes
__________

16 Jan: files set up; grid coded; first PR
___________

## Testing
________
Testing accomplished using inline testing in `chess_board.ipynb`.  The program must pass the provided tests given in the file as well as any custom tests coded by the developer

1. queens on same row should be “under attack”

2. queens on same column should be “under attack”

3. queens on same diagonal should be “under attack”

4. queens with any other coordinates should NOT be “under attack”
____________


