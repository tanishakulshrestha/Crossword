# Crossword
This project is part of CS50’s Introduction to Artificial Intelligence with Python by Harvard University. It implements an AI-based crossword puzzle generator using Constraint Satisfaction Problems (CSPs).
# Project Overview
The goal of this project is to automatically generate a valid crossword puzzle given:
A crossword structure (grid layout)
A list of words
The AI assigns words to crossword slots such that:
All words fit their slot lengths (unary constraints)
Overlapping words have matching letters (binary constraints)
No word is repeated
The solution uses node consistency, arc consistency (AC-3), and backtracking search with heuristics.

▶️ How to Run
-> Make sure you have Python 3.12 installed.
-> Run in terminal : 
python generate.py data/structure1.txt data/words1.txt

-> Generate crossword as an image : 
python generate.py data/structure1.txt data/words1.txt output.png
