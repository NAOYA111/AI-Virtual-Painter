python version - 3.11.0

Libraries required to install :
pip install mediapipe
pip install opencv-python

To convert exe (command used):

1.First Install pyinstaller 
2.pyinstaller --onefile --windowed --collect-data mediapipe  --add-data "header/*;header/" --add-data "handtrackingmodule.py;." painter.py


; ) enjoy the Ai Virtual Painter!