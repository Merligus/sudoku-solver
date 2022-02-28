# Sudoku solver
Sudoku solver. To test it you must:

1. Clone the repository
   ```sh
   git clone https://github.com/Merligus/sudoku-solver.git
   cd sudoku-solver/
   ```
2. Set the game.txt with 0 for empty spaces and numbers [1-9] for fixed spaces.
3. Compile
    ```sh
    g++ main.cpp -o solver
    ```
4. Run
	1. the default game.txt instance
	    ```sh
	    ./solver
	    ```
    2. the specified game2.txt instance
    	```sh
	    ./solver game2.txt
	    ```
5. The answer will be printed in the final.
