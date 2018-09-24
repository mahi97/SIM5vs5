# SIM5vs5
~ AUTCUP Soccer Simulation Platform for Miro-Middle (5vs5)

FIRA SimuroSot Middle League


README

SimuroSot5: SimuroSot Miro-Middle Game

-----


This is the 2018 FIRA SimuroSot Miro-Middle Game environment.

OS: Windows 7
Development Environment: Visual Studio 2010

1. Installation
You can go to: http://...... to download the Installation package.

2.Run the program 

Running SimuroSot5.exe will start the platform. (Don't change the path of installation)

3. File Explaination

3.1 The file structure

```
c:\Strategy
│   SimuroSot5.exe
│   WorldModel.exe
│   Referee.dll
│   Strategy4Blue.dll
│   Strategy4Yellow.dll
└───blue
│   │  Team1.dll
│
└───yellow
│   │   Team2.dll
│
└───src
    │   Strategy4Blue
    │   Strategy4Yellow
```


3.2 details explaination for the files
1. SimuroSot5.exe
>This is the start-up program. When it is running, it will start all the necessary program. After started, click the "Start" button on the dialog will start the game.You can pause the game by clicking the "Pause" button, and you can exit the game by clicking the "Close" button.

2. WorldModel.exe
>This is the original platform for middle league SimuroSot. It runs the world model for the game.

3. Referee.dll
>This is the computer referee module for judging the ongoing situations.

4. Strategy4Blue.dll
>The dll file that blue team should provide for the game

5. Strategy4Yellow.dll
>The dll file that yellow team should provide for the game

