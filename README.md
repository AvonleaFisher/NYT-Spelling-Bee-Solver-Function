# NYT-Spelling-Bee-Solver-Function
A function to return valid words to solve the NYT Spelling Bee puzzle

<b>Author:</b> Avonlea Fisher

<b>Blog Post: </b> [Solving the New York Times Spelling Bee Puzzle in Python](https://towardsdatascience.com/solving-the-new-york-times-spelling-bee-puzzle-in-python-511bcb5ea65e), published in [Towards Data Science](https://towardsdatascience.com/)

## About 
The contents of this repository comprise a program to automatically solve the [New York Times Spelling Bee](https://www.nytimes.com/puzzles/spelling-bee) given a set of constraints defined by the puzzle. A puzzle contains seven letters in a 'hive,' including a 'center letter.' In the below example puzzle, the center letter is 'L.' The goal is to create the maximum number of words that must contain the center letter and may only contain letters within the hive (repeats are allowed). Valid words must be relatively common and at least four letters long. In the puzzle below, 'alfalfa' would be an example of a valid word, while 'can' would be invalid (too short, no center letter). 

<img src="https://github.com/AvonleaFisher/NYT-Spelling-Bee-Solver-Function/blob/main/Images/Screen%20Shot%202021-01-11%20at%207.24.57%20PM.png"></a>
> Image of the January 11th, 2021 New York Times Spelling Bee puzzle


## Repository Files
* [words.txt](https://github.com/AvonleaFisher/NYT-Spelling-Bee-Solver-Function/blob/main/words.txt): A text file containing approximately 25,500 English words.
* [NYT Spelling Bee Solver.ipynb](https://github.com/AvonleaFisher/NYT-Spelling-Bee-Solver-Function/blob/main/NYT%20Spelling%20Bee%20Solver.ipynb): A Python notebook containing code for valid word list generation.

## Limitations
The text file contains a non-exhaustive set of words, which means that some words that are valid for a Spelling Bee puzzle may not appear in the solver's output. Additionally, not all of the output words will be valid entries for the puzzle. The puzzles are curated to exclude highly obscure words, which are not systematically excluded by the solver.

## For Further Information
Please contact me at fisheravonlea@gmail.com or via my [LinkedIn profile](https://www.linkedin.com/in/avonlea-fisher/).

