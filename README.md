Snake-Water-Gun-Game-Using-GUI

The Snake-Water-Gun game in Python 🐍💧🔫 is built using the Tkinter library. Play against the computer with interactive images and results.

🎮 Game Rules
- Snake drinks Water 🐍 > 💧
- Water drowns Gun 💧 > 🔫
- Gun kills Snake 🔫 > 🐍
- If both choose the same → it's a Draw

Features:
- GUI built with Tkinter
- Uses images for Snake, Water, and Gun
- Interactive buttons for choice selection
- Displays result with player & computer choices
- Restart and Exit buttons included

Functions Explained:
- downloading() → Downloads images (Snake, Water, Gun) from the internet.
- firstscreen() → Displays the welcome screen with images and Start button.
- startgame() → Clears first screen and moves to selection buttons screen.
- buttonscreen() → Shows Snake, Water, Gun buttons for the player to choose.
- game(human) → Handles the main logic: compares player vs computer choice and decides win/lose/draw.
- show_result_screen(human, comp, result) → Displays both choices and the game result with restart/exit options.
- restart_secondsreen() → Restarts the game by going back to the choice screen
- show_info() → Displays instructions using a message box.
- exit_func() → Confirms exit and closes the app.

Screenshot Example:
<img width="854" height="587" alt="image" src="https://github.com/user-attachments/assets/6453aeac-a5bd-4bd0-b3fb-fe99249ab442" />

Credits: 
- Developed in Python (Tkinter + Pillow)
- Images fetched online using requests

Requirements: 
pip install pillow
pip install requests

