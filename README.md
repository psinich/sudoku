# sudoku
Picture sudoku solver

## Main idea
The first thing the sudoku image does is locate the field itself, after which it is cut out and put through a perspective transformation to align it. 
Next, the field is sliced into 81 cells and each cell goes through Tesseract-OCR recognition to extract the digits.
Once extracted, the field is passed to the Backtracking algorithm for solving and a picture is created based on the solved sudoku 
