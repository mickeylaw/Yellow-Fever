README 

YELLOW FEVER v1.0 by 
GROUP ONE 

G54PRG PYGAME PROJECT 

INSTALLATION How-to (as tested on MacOS) 
---------------------------

1. Install Python 3.x (recommended - but not 3.8x as pygame is not compatible as of Dec 2 2019) 2.x from [here](https://www.python.org/download/releases/)

2. Install [pipenv]

2. Install PyGame 1.9.x from [here](http://www.pygame.org/download.shtml)

3. Download as zip and extract.

4. In the root directory run

```bash
$ pipenv install
$ pipenv run python YELLOWFEVER.py
```

5. Use <kbd>&uarr;</kbd> or <kbd>Space</kbd> key to play and <kbd>Esc</kbd> to close the game.

(For x64 windows, get exe [here](http://www.lfd.uci.edu/~gohlke/pythonlibs/#pygame))


NOTABLE FORKS 
-------------

- [FlappyBird Fury Mode](https://github.com/Cc618/FlapPyBird)
- [Pygame-Tutorial - Tech with Tim] (https://github.com/techwithtim/Pygame-Tutorials)

CREDITS
--------
https://www.gameart2d.com/freebies.html for game image assets 

DEVELOPMENT LOG
--------
Version 1. Motion animations were added for the girl
Version 2. The love letters were added as a bullet class object
Version 3. Hitboxes were implemented for the boy and girl
Version 4. A highscore function was created
Version 5. Sound assets were added to the game
Version 6. An instruction screen was added
Version 7. Start / Gameover / Countdown screen added 
Version 8. Debugging


TROUBLE SHOOTING
----------------
1) If you get this error "error: Couldn't open imgs\<image_name>.png", please check to ensure that the imgs folder is 
   placed in the same directory as YELLOWFEVER.PY
   
2) If the highscores are not auto updating, please ensure that highscore.txt is placed in the same directory
   as YELLOWFEVER.PY


ROAD MAP
--------
Additional levels could be added with different enemy variety

FILE DIRECTORY 
--------------
Enclosed In Zip File:

YELLOWFEVER.py
README.txt
DESCRIPTION.txt
highscore.txt
[FOLDER - GAME ASSET - DO NOT REMOVE OR CHANGE DIRECTORY]sounds 
[FOLDER - GAME ASSET- DO NOT REMOVE OR CHANGE DIRECTORY]imgs 
+Individual Peer Assessment(.csv) & Contribution file 