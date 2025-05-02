<h1 style="color: #4A90E2; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background-color: #E6F0FA; padding: 15px; border-radius: 10px;">
    Sudoku Solver - C++ Implementation
</h1>

<h2 style="color: #2C3E50; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">🎯 Objective</h2>
<p style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #34495E;">
    The objective of this project is to solve a Sudoku puzzle using a backtracking algorithm implemented in C++.
    The program fills in empty cells by testing numbers (1-9) and ensuring they adhere to Sudoku rules.
</p>

<h2 style="color: #2C3E50; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">🛠️ Tools</h2>
<ul style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #2D3436; list-style-type: circle; padding-left: 20px;">
    <li style="color: #1ABC9C;">C++ (Compiler supporting C++11 or higher)</li>
    <li style="color: #1ABC9C;">Standard C++ Library (vector, iostream)</li>
</ul>

<h2 style="color: #2C3E50; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">📦 Deliverables</h2>
<ul style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #2D3436; list-style-type: square; padding-left: 20px;">
    <li>Source code in a <strong>.cpp</strong> file</li>
    <li>Working example of a Sudoku board, with the solution printed in the console</li>
</ul>

<h2 style="color: #2C3E50; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">💡 Hints / Mini Guide</h2>
<div style="background-color: #FDF2E9; border-left: 6px solid #E67E22; padding: 15px; margin: 10px 0; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">
    <h3 style="color: #D35400;">Backtracking Algorithm Essentials</h3>
    <ul style="padding-left: 20px;">
        <li>Use a recursive backtracking approach to test each possible number in each empty cell.</li>
        <li>Validate each number based on the Sudoku rules: no duplicate numbers in rows, columns, or 3x3 subgrids.</li>
        <li>Use the <strong style="color: #8E44AD;">checker</strong> function to validate a number placement.</li>
        <li>Implement the <strong style="color: #3498DB;">sudoku_maker</strong> function to solve the board recursively.</li>
        <li>Print the board before and after solving to visually verify the solution.</li>
    </ul>
</div>

<h2 style="color: #2C3E50; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">🧠 Key Concepts Used in This Implementation</h2>
<ul style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #2D3436; list-style-type: disc; padding-left: 20px;">
    <li>Backtracking algorithm to solve the puzzle by trial and error</li>
    <li>Recursive function calls to navigate through the Sudoku grid</li>
    <li>Use of 2D vectors to represent the Sudoku board</li>
    <li>Validation of number placement using checks for rows, columns, and 3x3 subgrids</li>
    <li>Handling of the empty cells represented by '.'</li>
    <li>Printing the board using a formatted display with grid separation</li>
</ul>

<h2 style="color: #2C3E50; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">📑 Example Usage</h2>
<p style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #34495E;">
    The program initializes a Sudoku board with some pre-filled values and empty spaces (represented by '.'). 
    It then proceeds to solve the puzzle and prints the board before and after solving it.
</p>

<h2 style="color: #2C3E50; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">🧩 Sample Sudoku Board</h2>
<pre style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #34495E;">
    5 3 . | . 7 . | . . .
    6 . . | 1 9 5 | . . .
    . 9 8 | . . . | . 6 .
    ---------------------
    8 . . | . 6 . | . . 3
    4 . . | 8 . 3 | . . 1
    7 . . | . 2 . | . . 6
    ---------------------
    . 6 . | . . . | 2 8 .
    . . . | 4 1 9 | . . 5
    . . . | . 8 . | . 7 9
</pre>

<h2 style="color: #2C3E50; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">🚀 How to Run</h2>
<ol style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #34495E;">
    <li>Clone or download the source code file.</li>
    <li>Compile the code using a C++ compiler (e.g., <code>g++ sudoku_solver.cpp -o sudoku_solver</code>).</li>
    <li>Run the executable to see the Sudoku puzzle being solved (e.g., <code>./sudoku_solver</code>).</li>
</ol>


