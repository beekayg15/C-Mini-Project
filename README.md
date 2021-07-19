# Bulls and Cows WebPage

A **project** bringing to life, the digital version of the primitive **Bulls and Cows game**, created using `C` language.

## Tools and Languages Used :
<p>
<img width="45" height="45" hspace="10" src="https://github.com/BarathKumarBK-15/BarathKumarBK-15/blob/main/icons/3.png"/>
<img width="45" height="45" hspace="10" src="https://github.com/BarathKumarBK-15/BarathKumarBK-15/blob/main/icons/5.svg"/>
</p>

## Download and Usage :
The code can be downloaded as a compressed `zip` file from the github web interface.

The repository can also be cloned using:
```
git clone https://github.com/BarathKumarBK-15/C-Mini-Project.git
```

The game can be deployed locally after extraction by compiling and running the `main.c` file using the sequence of code in the terminal:
```
gcc main.c -o bcgame
```
```
./bcgame
```

## Components of Project :
- **C** files - 1

## About the Game :
The game contains multiple pages namely, _Home_, _Instruction_, _GamePlay_, _Previous Result_, which together provide a simple yet elegant interface for the gameplay. The various components and phases of the game are explained below 

- **Home** :
  - The page provides a variety of options for the user to choose between in the beginning of the game.
  - The user can choose to start the game, read the instructions, view the past result or exit from the game.
  
- **Instructions** :
  - The page displays the **basic instructions** of the game, grouped into three categories.
  - It provides a brief **description** of the game and explains the mystery behind the keywords of the game.
  
- **View Past Results** :
  - The page displays the **history** of matches played and their **outcomes**.
  - This is achieved via the concept of `file handling`.
  - The results of every game is stored in a simple `.txt` file, that can be invoked when required.
  
- **GamePlay** :
  - The game initiate with the choosing of **difficulty level** that determines the **number of digits** in the **key**.
  - The game provides both single player an multiplayer modes.
  - In the **single player mode**, the player is required to find the secret random key code set by the computer.
  - In the **multiplayer mode**, the players can set each others key.
  - The task of the player to figure out the secret key in **minimum number of turns**.
  - The game provides hints for each guess by returning the **number of bulls and cows**, with which the user's **closeness** to the solution can be known
  
- **Algorithm** :
  - The program provides an **efficient algorithm** for the game.
  - The `algorithm` is executed using simple `Data-Structures` like `Arrays` and basic concepts of `Functions` and `Loops`.
  - The `algorithm` contains seperate function to **calculate** the **number of bulls and cows** using `linear search`.


**Note** : 
The game has been further developed using `HTML5`, `CSS3` and `JavaScript` with a better graphical model and an interactive user-friendly layout. Click on the link below for more details.

Project Link: https://github.com/BarathKumarBK-15/BullsandCowsWebPage

Game Link: https://barathkumarbk-15.github.io/BullsandCowsWebPage

## Contributors
- <a href="https://github.com/Aravindkrish25"> Aravind M </a>
- <a href="https://github.com/BarathKumarBK-15"> Barath Kumar G </a>
- <a href="https://github.com/Bhooshaan"> Bhooshaan A </a>
- <a href="https://github.com/Hrithik1702"> Hrithik B </a> 