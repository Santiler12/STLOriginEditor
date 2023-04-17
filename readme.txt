1. Install Python for your windows computer (https://www.python.org/downloads/)
2. Open a "Windows PowerShell" app with Admin privileges
3. Check if Python has been properly installed running this command:
py --version
4. If Python is installed correctly you should receive a response similar to (Python 3.11.3)
5. Run the following commands:
py -m pip install --upgrade pip
py -m pip install numpy
py -m pip install python-utils
py -m pip install numpy-stl
6. Link your .py files to Python - right click on the ForSetup.py file on this folder -> then Open With -> more apps -> look for another app on this pc -> locate phyton.exe
Make sure to click the "always use this app to open .py files"

NOTE: If you have difficulty finding the location of the "python.exe" file run the following command on Windows PowerShell
py -c "import sys; print(sys.executable)"




