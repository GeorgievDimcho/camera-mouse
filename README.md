# camera-mouse
This is a camera mouse software dedicated to people with motor disabilities. This project implements an assistive human computer interface with the help of face tracking. Easy to configure graphical user interface was created with the python library Tkinter.

In Version 1.0 the distance between the camera and the face does not have to be 35 cm. The code detects the face from distance between 5cm and 150 cm.

If you are windows user download the "camera-mouse.exe" file from the follwing link: https://cloud.technikum-wien.at/s/JgErfESpiWzqLen (Github does not allow upload of files larger than 100MB). If you want to further develop the software you will need to install the requirements first. In order to do that execute the following command in CMD(Windows) or Terminal(Linus/MAC):
In order to create a virtual enviroment: (This step need to be done only once)
``` 
python3 -m venv camera_mouse_venv
``` 
In order to activate the virtual enviroment under windows please follow the instruction here : https://python.land/virtual-environments/virtualenv 
In order to activate the virtual enviroment under linux: (This step need to be repeated for every start)
``` 
source camera_mouse_venv/bin/activate
``` 
In order to install the required libraries: (This step need to be done only once)
``` 
  pip install -r requirements.txt
```
In order to run the source execute the follwing command: (This step need to be repeated for every start)
```
   python3 camera-mouse.py
```
In order to allow simplicity a batch script is in development which will allow to install python and all required libraries and start the appliation with simple mouth click.
