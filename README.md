Python program to automatically join the online zoom classes 
based on the given input in the Excel sheet List.xlsx

the input should be in the given format:

Time : dd-mm-yyyy hh:mm AM/PM

Meeting ID : 123456123 (string)

Meeting Password : 1234 (string)

IMP - If you want to change the program path jump to line 40

Disclaimer:
I am not responsible for any troubles caused to you
if the program does not function as intended, or if it is misused,
please make sure to test it before executing

Modules used:

pyautogui - https://pyautogui.readthedocs.io/en/latest/

openpyxl - https://openpyxl.readthedocs.io/en/stable/

PIL - https://pillow.readthedocs.io/en/stable/


Pre-Requirements:

Windows machine

Zoom app

Web browser (chrome, firefox preferred ,make sure it has pop-up enabled to open zoom app)

Python - Download and install from https://www.python.org/downloads/

Steps:

1)open command prompt and type (installing modules - pyautogui, openpyxl, Pillow) (this is required only for the first time)

	pip install pyautogui
	(let it install)
	pip install openpyxl
	(let it install)
	pip install Pillow==7.1.1
	(let it install)
	pip install opencv-python
	(let it install)


2) open List.xlsx
enter the schedule of the day in the excel sheet
 in the correct columns in the correct format
 
	Time : dd-mm-yyyy hh:mm AM/PM
	Meeting ID : 123456123 (string)(not required if meeting link is provided)
	Meeting Password : 1234 (string)(not required if meeting link is provided)

Warning : please enter as given

3) make sure to close all windows and free up the desktop
(my program runs on Image Recognition :D )

	run Auto.py
	
4) Do not close the command prompt thats where the program is running 
	and any errors show up
5) keep an eye out in case of errors and failures
	I am not responsible for any troubles caused to you
	if the program does not function as intended, or if it is misused,
	please make sure to test it before executing
	
Errors:

I have to admit I should still do proper error handling, but if you followed the steps 
correctly there should not be any problems
just in case there are fail safe measures:

1) Mouse losing control : quickly move the mouse as far up and left as you can
2) program stuck in infinite loop : in the command prompt spam CTRL + C, re-run Auto.py to restart
3) any other errors will show up in the command prompt window if not it ll close re-run Auto.py to restart
4) do not let the computer sleep when there is long intervals between lectures

If any problem still persists repeat Steps 1-5, and hit me up

and the images required are hidden for proper functioning of the program in case you want to modify,
you have my permission to change the code and use it as per your wish

Future Plans:

To record the classes I dont have any ideas currently if you have please do share it with me
