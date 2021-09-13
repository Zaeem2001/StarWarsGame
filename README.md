# Star Wars: The Non-Profit Game
## Made by Zaeem Ghauri

### What is this?

This project was submitted as my final assignment for my grade 12 computer programming class. It was my first ever experience with programming and a lot of it was self-taught, quick-and-easy fixes, hence why the code looks... like that. It was developed in Java using multiple libraries centered around graphical user interface. The project itself is an old school, Galaga-type shooter game with a Star Wars theme. Despite the poor code, the game plays very well and to this day I'm proud of what I accomplished and wanted to share it with others. 

-----

### Set Up

The set up for this project is fairly easy:

1. Pull or copy and paste the "StarWarsGame" file from the repository it into a new project/class using a Java IDE of your choice.
   
   *NOTE: You must run the progam with an older Java since applet's only work with jdk-8 and below. I'd recommend the "ReadyToProgram" IDE if you are not a programmer and simply want to play the game.*
   
2. Follow <a target="_blank" href="https://drive.google.com/drive/folders/1z-X09ZHRQ-5biIMKvnJcdgYUXVnU3t4M?usp=sharing">this link</a> to a folder of the game's assets and download them. 
   
3. Place the game's code (from step 1) in the same folder as the assets.

4. Open the game's code and at the very beginning edit the CLASSNAME and the "path" variable.
   - change the CLASSNAME to match the name of the class you created with your IDE
   - change the "path" to the address of the "highscore.txt" file in the folder in which the game is saved.

-----

### How to Play

1. Run the program to open up an applet window that will display the game.

2. The first thing you'll see is the menu screen with three buttons:
   - "Highscores" allows you to see the top 10 (local) scores saved into the "higscore.txt" file
   - "Choose Ship" allows you to choose from 3 different space ships, each with different health, hitboxes, and speed
   - "Play" allows you to start the game with the ship you've chosen

3. Once you start the game you'll see a HUD at the very top. From right to left, it displays your ammunition, the level/difficulty you're playing at, the amount of lives you have left, and your current score.

4. The objective of the game is to avoid hitting the obstacles and survive as long as possible. As you progress, you'll be faced with more obstacles such as incoming spaceships, a bomb, and lasers. Get a score of over 10000 and you'll be met with a little surprise at the end...

5. Move the spaceship with your mouse. Increase your score faster by moving your mouse up the screen, although this makes your spaceship fly faster and makes it harder to avoid obstacles. You could also play it safe and move your mouse down the screen to slow down your spaceship.

6. Left-click your mouse to shoot your ammunition and destroy the incoming enemy ships. But be careful! There are only 10 rounds of ammunition given at a time. After you fire all 10 you'll have to wait a bit for your ammunition to reload.

7. There are 2 power-ups that will be floating around during the game: a health orb which grants you an extra life, and a shield orb which grants invulnerability for a limited time. Going out of your way to grab them could either extend your run or end it...

8. Once you run out of lives it's game over. You'll be taken to a screen where you can enter your highscore (if you made one). Yoda will give you some words of encouragement and ask if you'd like to play again which will take you to the main menu.

-----

### Visit [my website](https://zaeem2001.github.io/projects/starwarsgame.html) to see my project in action!
