#GAME OF DRAGONES
##Game of Thrones Themed "Snake"

##setup:


install python 2 or 3 (https://www.python.org/downloads/)


install the pyopengl libraries:

###windows:
  
download the pre-built libraries from here http://www.lfd.uci.edu/~gohlke/pythonlibs/#pyopengl which should include the relevant opengl and glut libs
  

use:

```
pip.exe install XXXX.whl to install
```


*NOTE* pick the correct whl file for your python installation, ie. you may be running python 32bit on a 64bit system. if so install 32bit whl version.

  
*NOTE* pip or python may not be on the PATH so explicit direction may be necessary. python is usually installed to c: and pip is located in the c:\pythonXX\Scripts direrctory
  
  
###linux:
  
install the opengl and glut libs (also python-pip - which is seperate in some repos)
  
use: pip install PyOpenGL

  
---


##to start:

python Snake.py - *initializes a new score-board default name of TeamSaved_NNNNNNNNNNNNN.txt*

python Snake.py "teams.txt" - *uses a file to initialize or use existing scoreboard*


##format of "teams.txt":

###for game initialization:

```
TEAMNAMES
team1
team2
team3
..
.
teamN
```

otherwise "teams.txt" is a "pickle" of the currently playing teams status.


---


##playing:

**SPACE** starts (or returns to menu during countdown)

**UP/DOWN/LEFT/RIGHT** - guides dragon

**LEFT/RIGHT** - guides dragon during snake-cam

