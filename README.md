## BigTicTacToe

### Main Menu  
<img src="/.gitresource/MainMenu.png">

### Game Mode Selection  
You can choose between the classic mode (3×3), a large grid mode (9 boards of 3×3 — essentially a 3×3 inside another 3×3), or create a custom setup.  
<img src="/.gitresource/SelectTypeGame.png">

### Game Mode Settings  
In this menu, you can configure the board size, including non-symmetrical grids (for example, 2×4), and choose between the classic mode or the multi-board mode (Big Tic Tac Toe).  
<img src="/.gitresource/CustomGame.png">

### Big Tic Tac Toe Mode  
In the classic version of this mode, there are 9 boards (3×3), each containing its own 3×3 grid. The first move can be made anywhere, but each subsequent move depends on the previous one.  

If you make a move in a small board cell located in the bottom-left position, the next move must be made in the corresponding bottom-left board of the larger grid (if available). If that board is already closed or unavailable, the next move can be made in any board.  

When a player gets three in a row on a small board, that board is captured and visually marked (filled in).  

<img src="/.gitresource/GameStep1.png"><br>
<img src="/.gitresource/GameStep2.png"><br>

The winner is the player who gets three in a row on the large board.  

<img src="/.gitresource/GameWin.png"><br>