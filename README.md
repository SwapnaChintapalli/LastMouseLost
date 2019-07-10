# LastMouseLost
Artificial Intelligence

Final Project:
CS 6364.001 Artificial Intelligence
Swapna Chintapalli - SXC180048


Files Included:
==================================================
last_mouse_lost.py - Main program to read input and call algorithm to solve problem.
board.py - Consists initial board configuration.
player.py - Implements player functionalities.
smart_player.py - Implements smart player moves.
Report.pdf - Project Report.


Instructions to run program:
==================================================
IDE used Eclipse Photon Release (4.8.0)
Python: 3.7
- Create new Python Project.
- Paste the folder SXC180048 inside project.
- Run last_mouse_lost.py
	Displays initial boadr configuration.
	Input:	enter row number
		enter amount: //How many dots
			
			
			

Sample Input and its corresponding output:
==================================================

After running last_mouse_lost.py: 
==================================================
	Welcome to Last Mouse Lost Game:
==================================================
	Row 0          o   o   o   
	Row 1      o   o   o   o   o   
	Row 2    o   o   o   o   o   o   
	Row 3    o   o   o   o   o   o   
	Row 4      o   o   o   o   o   
	Row 5          o   o   o   

**************************************************
Enter Row: 1
Enter Amount: 3

Human Player 0 made move (1, 3)

---------------------------------------------------

	Row 0          o   o   o   
	Row 1      x   x   x   o   o   
	Row 2    o   o   o   o   o   o   
	Row 3    o   o   o   o   o   o   
	Row 4      o   o   o   o   o   
	Row 5          o   o   o   

**************************************************

Smart Player 1 made move (4, 3)

---------------------------------------------------

	Row 0          o   o   o   
	Row 1      x   x   x   o   o   
	Row 2    o   o   o   o   o   o   
	Row 3    o   o   o   o   o   o   
	Row 4      x   x   x   o   o   
	Row 5          o   o   o   

**************************************************
Enter Row: 2
Enter Amount: 4

Human Player 0 made move (2, 4)

---------------------------------------------------

	Row 0          o   o   o   
	Row 1      x   x   x   o   o   
	Row 2    x   x   x   x   o   o   
	Row 3    o   o   o   o   o   o   
	Row 4      x   x   x   o   o   
	Row 5          o   o   o   

**************************************************

Smart Player 1 made move (3, 4)

---------------------------------------------------

	Row 0          o   o   o   
	Row 1      x   x   x   o   o   
	Row 2    x   x   x   x   o   o   
	Row 3    x   x   x   x   o   o   
	Row 4      x   x   x   o   o   
	Row 5          o   o   o   

**************************************************
Enter Row: 1
Enter Amount: 1

Human Player 0 made move (1, 1)

---------------------------------------------------

	Row 0          o   o   o   
	Row 1      x   x   x   x   o   
	Row 2    x   x   x   x   o   o   
	Row 3    x   x   x   x   o   o   
	Row 4      x   x   x   o   o   
	Row 5          o   o   o   

**************************************************

Smart Player 1 made move (4, 1)

---------------------------------------------------

	Row 0          o   o   o   
	Row 1      x   x   x   x   o   
	Row 2    x   x   x   x   o   o   
	Row 3    x   x   x   x   o   o   
	Row 4      x   x   x   x   o   
	Row 5          o   o   o   

**************************************************
Enter Row: 0
Enter Amount: 3

Human Player 0 made move (0, 3)

---------------------------------------------------

	Row 0          x   x   x   
	Row 1      x   x   x   x   o   
	Row 2    x   x   x   x   o   o   
	Row 3    x   x   x   x   o   o   
	Row 4      x   x   x   x   o   
	Row 5          o   o   o   

**************************************************

Smart Player 1 made move (5, 3)

---------------------------------------------------

	Row 0          x   x   x   
	Row 1      x   x   x   x   o   
	Row 2    x   x   x   x   o   o   
	Row 3    x   x   x   x   o   o   
	Row 4      x   x   x   x   o   
	Row 5          x   x   x   

**************************************************
Enter Row: 4
Enter Amount: 1

Human Player 0 made move (4, 1)

---------------------------------------------------

	Row 0          x   x   x   
	Row 1      x   x   x   x   o   
	Row 2    x   x   x   x   o   o   
	Row 3    x   x   x   x   o   o   
	Row 4      x   x   x   x   x   
	Row 5          x   x   x   

**************************************************

Smart Player 1 made move (1, 1)

---------------------------------------------------

	Row 0          x   x   x   
	Row 1      x   x   x   x   x   
	Row 2    x   x   x   x   o   o   
	Row 3    x   x   x   x   o   o   
	Row 4      x   x   x   x   x   
	Row 5          x   x   x   

**************************************************
Enter Row: 2
Enter Amount: 1

Human Player 0 made move (2, 1)

---------------------------------------------------

	Row 0          x   x   x   
	Row 1      x   x   x   x   x   
	Row 2    x   x   x   x   x   o   
	Row 3    x   x   x   x   o   o   
	Row 4      x   x   x   x   x   
	Row 5          x   x   x   

**************************************************

Smart Player 1 made move (3, 2)

---------------------------------------------------

	Row 0          x   x   x   
	Row 1      x   x   x   x   x   
	Row 2    x   x   x   x   x   o   
	Row 3    x   x   x   x   x   x   
	Row 4      x   x   x   x   x   
	Row 5          x   x   x   

**************************************************
Enter Row: 2
Enter Amount: 1

Human Player 0 made move (2, 1)

---------------------------------------------------



Human Player 0 Lost
