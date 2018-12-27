### FACIAL RECOGNITION ATTENDANCE MANAGENMENT (FRAM)


Description of the environment I have run this project:
1. Windows 10 64 bit.
2. WAMP server.
3. Python 2.7

python plugins requried:
1. numpy
2. Tkinter
3. CV2
4. CV
and others...

## Directory Description:

#Folders: 
1. eigenfaces, reconfaces: Contains the auto generated intermediate data after evaluation.
2. face: Contains database of faces and other modules for evaluation
3. haarcascades: Contains all the algorithm needed for evaluation (only Face comparison algorithm)
4. include, lib, libs, Scripts, share, tcl, tools: Contains built-in python files.

#Files:

1. Main.py: Contains GUI elements. Calls all the other modules using GUI.
2. capture_group_image.py: Captures group image
3. face.py: performs detection and cropping.
4. faceRecognition.py : Performs face recognition.
5. facultyLogin.py: Faculty login module using credentials.
6. resize.py: Performs image resizing.

It is advised to clone this project inside python installed folder.
{: .notice}
