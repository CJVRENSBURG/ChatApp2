# ChatApp2
a Chat app build with Kivy-Python
---------------------------------

HOW TO RUN THE APP:

You have to create a virtualenvironment to install kivy.

If you're on Windows:
- virtualenv <the name of virtualenvironment>
- <the name of virtualenvironment>\Scripts\activate
  
If you're on Linux/MacOs:
- virtualenv <the name of virtualenvironment>
- source <the name of virtualenvironment>/bin/activate
  
To deactivate the environment:
- deactivate

The modules to install:

1. python -m pip install --upgrade pip wheel setuptools virtualenv
2. python -m pip install docutils pygments pypiwin32 kivy_deps.sdl2==0.1.22 kivy_deps.glew==0.1.12
3. python -m pip install kivy_deps.gstreamer==0.1.17
4. python -m pip install kivy==1.11.1
