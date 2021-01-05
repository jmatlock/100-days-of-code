# 100 Days Of Code - Log

### Day 0: December 28, 2020

**Today's Progress:** Setup Sudoku Solver project, read in puzzle file, check for validity and completeness, generate candidates for empty squares

**Thoughts:** In actuality, this is the result of two days work, but I am officially starting today. Shaking off some holiday cobwebs. Doing some cool
things with sets, generators, and formulas with the sudoku array.

**Link to work:** [Sudoku Solver](https://github.com/jmatlock/SudokuSolver)

### Day 1: December 29, 2020

**Today's Progress:** Used "naked singles" to solve easy puzzles. Incorporated timer class to measure performance.

**Thoughts:** Using a naive solution was able to solve many "hard" sudokus just using the "naked singles" method. Research of backtracking but no implementation yet,
I'm considering how efficient I want to make the backtracking, possibly leveraging the number of candidates for squares.

**Link(s) to work:** [Sudoku Solver](https://github.com/jmatlock/SudokuSolver)

### Day 2: December 30, 2020

**Today's Progress:** Added tkinter GUI for interactive element and displayed sudoku in grid. No actual interactive elements yet.

**Thoughts:** I debated whether to use pygame or tkinter and decided to learn the "classic" first. Will take me a bit to wrap my head
around implementing the event loop properly.

**Link(s) to work:** [Sudoku Solver](https://github.com/jmatlock/SudokuSolver)

### Day 3: December 31, 2020

**Today's Progress:** Moved tkinter GUI into its own class and did a basic animation of the program solving via naked singles. First interactions with the GUI via a button.  Dynamic updates of the labels.

**Thoughts:**  Project is growing! Definitely see this project being a bigger challenge if and when I allow users to enter their own solutions. 
Maybe I need to include fields instead of labels for blanks? This project feels MUCH bigger than what I originally thought. Feature creep for sure.

**Link(s) to work:** [Sudoku Solver](https://github.com/jmatlock/SudokuSolver)

### Day 4: January 1, 2021

**Today's Progress:** Implemented a not optimal version of backtracking in command line version.

**Thoughts:** This work was a bit more difficult than expected due to my choices on data structures. As I traversed, I needed to clean up "guesses" when I backtracked. Still I managed to get it working. It will be interesting to include this in the GUI. Unclear if I will continue beyond that point or set aside and move on to something else.

**Link(s) to work:** [Sudoku Solver](https://github.com/jmatlock/SudokuSolver)

### Day 5: January 2, 2021

**Today's Progress:** The backtracking solution is animated in the UI. Made the animation more flexible so any additional methods can more easily update the grid. 

**Thoughts:** Did some work improving the structure and it really is starting to shape up. I'm about to a point where I may declare a version of this "done enough" and
move on to another project. Considering the Matrix Clock and a web based random task generator.

**Link(s) to work:** [Sudoku Solver](https://github.com/jmatlock/SudokuSolver)

### Day 6: January 3, 2021

**Today's Progress:** Started RGB LED Matrix Clock project, starting with code from Adafruit Moon Clock. Up and running with stock code, no changes yet.

**Thoughts:** Took time building out the structure of the project in Pycharm and finding a way to do a workflow where I have to copy code from the Pycharm project
to the Matrix Portal drive. I want to improve this workflow, maybe using the Micropython plugin. Also, need to point to a different time server as the one being used
in the Moon Clock project seems to be prepetually busy and unable to provide time of day info.

**Link(s) to work:** TBD

### Day 7: January 4, 2021

**Today's Progress:** Changed base code to simpler Adafruit Network Clock project. Added day of week and date to display.

**Thoughts:** The Moon Clock project is quite complex and I wanted to simplify things to help me make better progress. Sometimes stepping back is a good choice. Looking forward to including weather info and having a two line display.

**Link(s) to work:** [Matrix Clock Plus](https://github.com/jmatlock/MatrixClockPlus)

<!---
### Day x: January xx, 2021

**Today's Progress:** 

**Thoughts:** 

**Link(s) to work:**
-->

