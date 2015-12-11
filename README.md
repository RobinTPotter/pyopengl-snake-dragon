# pyopengl-snake-dragon 

setup:

install python 2 or 3
install the pyopengl libraries:
  windows:
  download the pre-built libraries from here which should include the relevant opengl and glut libs, on linux 
  use pip.exe install XXXX.whl to install
  
  linux:
  install the opengl and glut libs(also python-pip - which is seperate in some repos)
  use pip install PyOpenGL
  
to start:

python Snake.py   ## initializes a new score-board
python Snake.py "teams.txt"  ##uses a file to initialize or use existing scoreboard

format of "teams.txt":

for game initialization:

TEAMNAMES
team1
team2
team3
..
.
teamN

otherwise teams.txt is a "pickle" of the currently playing teams status.

playing:

SPACE starts (or returns to menu during countdown)
UP/DOWN/LEFT/RIGHT - guides dragon
LEFT/RIGHT - guides dragon during snake-cam
