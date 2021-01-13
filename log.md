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

### Day 8: January 5, 2021

**Today's Progress:** Reading data from openweathermap.org and displaying the local temperature.

**Thoughts:** Was able to leverage another tutorial to grab the weather data. I'm now setup to move to a new phase where I'll go from a one line to two line display that will have some scrolling. It's been very interesting work and I'm pleased with the progress.

**Link(s) to work:** [Matrix Clock Plus](https://github.com/jmatlock/MatrixClockPlus)

### Day 9: January 6, 2021

**Today's Progress:** Added second line to display and seeded with static event data.

**Thoughts:** Getting the hang of adding static information to display, but I definitely see a challenge with doing animation (scrolling across). Next session I guess
I will building in some kind of update loop that moves the text across the display. Ugh.

**Link(s) to work:** [Matrix Clock Plus](https://github.com/jmatlock/MatrixClockPlus)

### Day 10: January 7, 2021

**Today's Progress:** Added "days until" and current weather conditions.

**Thoughts:** Nearly ready to declare this as MVP. Some frustration with choppy scrolling as card operations direction affect writing of display, but may decide it's just quirky and move on.

**Link(s) to work:** [Matrix Clock Plus](https://github.com/jmatlock/MatrixClockPlus)

### Day 11: January 10, 2021

**Today's Progress:** Added text color changing when up and down buttons on the Matrix Portal board are pushed.

**Thoughts:** On a whim I decided to play with the buttons on the Matrix Portal. I've also ready started planning the next project so I think I'll be done with this
one for a little while.

**Link(s) to work:** [Matrix Clock Plus](https://github.com/jmatlock/MatrixClockPlus)

### Day 12: January 11, 2021

**Today's Progress:** Started new project, Task Tracker, which is a Django web application. Created the initial project and added the simple data models for the tasks
and other supporting data.

**Thoughts:** It's been quite a while since I did anything with Django, and it's a little bit of a struggle getting back to it. But hopefully it will come back soon
and I'll be able to make quicker progress. I'd only like to spend about 5 days on the project, but we'll see.

**Link(s) to work:** [Task Tracker](https://github.com/jmatlock/TaskTracker)

### Day 13: January 13, 2021

**Today's Progress:** Created template view for the Task model, styled with Bootstrap 4

**Thoughts:** Pulling a bit from Django For Beginners by William Vincent but tweaking it along the way. Much more progress than I expected. Unsure how far I want 
to go with this project though. Still not that excited about the work, and I'm struggling (mentally) to keep going with this 100 days.

**Link(s) to work:** [Task Tracker](https://github.com/jmatlock/TaskTracker)

<!---
### Day x: January xx, 2021

**Today's Progress:** 

**Thoughts:** 

**Link(s) to work:**
-->

