🐍 Snake Game in C (Cross-Platform)
Hey everyone!
This is a simple Snake Game coded in pure C language, which runs perfectly on both Windows and Linux/Unix platforms.
I made this game using basic C concepts like structures, pointers, dynamic memory allocation, and a little bit of terminal handling (to detect key presses, clear screen, etc.).

📋 Features:
✅ Snake Movement (UP, DOWN, LEFT, RIGHT)

✅ Food Generation (Random)

✅ Score Tracking

✅ Speed Control (+ to speed up, - to slow down)

✅ Cross-Platform Compatible (works on Windows, Linux, Mac)

✅ Snake grows on eating food

✅ Snake dies on collision with itself (Game Over)

🖥️ Controls:
Key	Action
u	Move Up
d	Move Down
l	Move Left
r	Move Right
+	Increase Speed
-	Decrease Speed

⚙️ How to Run:
🔸 For Windows:
Open VS Code or any terminal.

Compile:
gcc snake_game.c -o snake_game

Run:
snake_game.exe

🔸 For Linux/Unix:
Open terminal.

Compile:
gcc snake_game.c -o snake_game

Run:
./snake_game

📦 Requirements:
GCC Compiler

Standard C Library

⚠️ Notes:
The game auto wraps around the walls (snake appears from opposite side).

Collision with the own body ends the game.

After Game Over, you can press 'y' to play again or any other key to exit.

📝 What I learned:
✔️ How to handle keyboard input without Enter key (Windows & Linux both).
✔️ Use of dynamic memory for linked list (snake body).
✔️ Cross-platform screen clearing and sleeping.
✔️ Making games in pure C without graphics library.

🤝 Contribution:
Want to improve or add something cool?
Feel free to fork, modify, and pull request! 😊

🎯 Author:
Vivek-kumar3011
