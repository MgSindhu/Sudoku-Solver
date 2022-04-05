# Sudoku-Solver

## Pipeline of the project

### 1. Preprocessing the image

First, we will convert into grayscale and apply some thresholding maybe some blur as well
### 2. Find the counters

Here, we'll find the counters to reduce noise and coordinates of the maximum area in image are found and also crop the image
### 3. Find Sudoku

Here, we will apply Warp Perspective and form individual grids on the image. These individual images will help in extracting out the smaller tiles which contain a single digit or blank
### 4. Classify digits

classify each of the digits, so that digits are clearly visible
### 5. Find Solution

Solves the sudoku using the Backtracking algorithm and the solution is shown on an empty sudoku grid


