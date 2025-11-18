
Killer Sudoku Project
=====================

Files:
- solver.py : core solver (KillerSudokuSolver)
- gui.py : Tkinter frontend to draw cages and solve

How to run:
1. Ensure you have Python 3.8+ installed.
2. Run the GUI:
   python /mnt/data/killer_sudoku_project/gui.py
3. Use the canvas to click cells to select them, then "Add Cage from Selection" to create cages and give them a sum.
4. Press "Solve" to try to solve the puzzle. You can also export/import JSON for puzzles.

Notes & Next steps:
- The solver implements cage-based reduction + MRV backtracking. It is designed to be understandable and extensible.
- For more advanced solving strategies, consider adding:
  - better cage adjacency handling, non-ordered combination mapping,
  - AC-3 arc consistency across cells,
  - a step-by-step explanation mode for visualization.
