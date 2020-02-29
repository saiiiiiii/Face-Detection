                                                              Face Detection
                                                              
How to clone this project Open VS Code TERMINAL ( Ctrl + ` ) or ( Ctrl + Shift + P)

git Clone

git clone https://github.com/saiiiiiii/Face-Detection.git

Open the folder you have just cloned ( File->Open Folder)

After Clone

first you have to upgrade your pip python -m pip install –upgrade pip

required packages (or) library

pip install streamlit opencv-python
numpy,
pandas,
PILLOW

System requirements:
Language: Python 3.8.2,
OS: Windows 10.

Create a new environment with Streamlit
Go to the folder where your project will live:

cd myproject
Create a new Pipenv environment in that folder:

pipenv
When you run the command above, a file called Pipfile will appear in myprojects/. This file is where your Pipenv environment and its dependencies are declared.

Install Streamlit in your environment:

pip install streamlit
Or if you want to create an easily-reproducible environment, replace pip with pipenv every time you instal something:

pipenv install streamlit
Test that the installation worked:

streamlit hello

Streamlit's Hello app should appear in a new tab in your web browser!

Use your new environment
Any time you want to use the new environment, you first need to go to your project folder (where the Pipenv file lives) and run:

pipenv shell
Now you can use Python and Streamlit as usual:

streamlit run app.py

Image Manipulation

Brightness using Pillow's.

Contrast,
Brightness,
Blurring

FaceDetected package:
https://github.com/opencv/opencv/tree/master/data/haarcascades
Detect Face,
Detect Eyes,
Detect Smiles,
Cartonize,
Cannize.
