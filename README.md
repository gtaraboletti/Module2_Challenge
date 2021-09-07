# Loan Qualifier App 

This program utilizes information from banks and information provided by the customer to try to find loans that the user is eligible to apply for. 
For the purposes of this assignment, all code was already provided except the save_qualifying_loans() function, which was written by the student. 

---

## Technologies

Coded in Python 3.8.8

Libraries Used: 
csv (included in Python install) - *provides functionality for manipulating .csv files*
fire 3.9.0 - *used to automatically create command line interfaces*
pathlib (included in Python install) - *provides object API for working with files and directories*
questionary 1.5.2 - *Allows for expanded command line interface features.* 
sys (included in Python install) - *provides functions and variables used to manipulate different parts of Python runtime environment* 

---

## Installation Guide

### To install python: 

go to the python website: [https://www.python.org/downloads/](https://www.python.org/downloads/)
Download version 3.8.8 (program may or may not work in newer or older versions)
[Python Installation Guide](https://wiki.python.org/moin/BeginnersGuide/Download)

### To install Fire and Questionary libraries: 

Step 1: Open Git Bash, Terminal, or other command prompt 
Step 2: In command prompt, type the following: 

```pip install fire```

Hit enter. When prompted, type "y" 

Step 4: In command prompt, type the following: 

```pip install questionary```

Hit enter. When prompted, type "y" 

---

## Usage

Step 1: Open the command prompt of your choice (Git Bash, Terminal, Anaconda Prompt, etc.)

![command prompts](https://raw.githubusercontent.com/gtaraboletti/Module2_Challenge/main/readme_images/step%201.png)

Step 2: Type `pwd` into the terminal and note the directory. (begins with /c/) 

![pwd](https://raw.githubusercontent.com/gtaraboletti/Module2_Challenge/main/readme_images/step%202%20check%20directory%20.png)

Step 3: Navigate to the correct directory by typing `cd` and the path to the directory where the program is saved.

![directory](https://raw.githubusercontent.com/gtaraboletti/Module2_Challenge/main/readme_images/step%203%20navigate%20to%20correct%20directory%20.png)

Step 4: Type in the command `python app.py` and hit enter

![app](https://raw.githubusercontent.com/gtaraboletti/Module2_Challenge/main/readme_images/step%204%20type%20python%20command%20and%20hit%20enter.png)

Step 5: Find the daily rate sheet file on your computer and copy the path to its location. 

![navigate](https://raw.githubusercontent.com/gtaraboletti/Module2_Challenge/main/readme_images/step%205%20navigate%20to%20daily%20rate%20sheet%20and%20select%20copy%20path.png)

Step 6: Paste path into your terminal and press enter. 

![path](https://raw.githubusercontent.com/gtaraboletti/Module2_Challenge/main/readme_images/step%206%20paste%20path%20and%20hit%20enter.png)

Step 7: Answer the questions by typing in the correct data when prompted. Hit the enter key after each response. 

![answering](https://raw.githubusercontent.com/gtaraboletti/Module2_Challenge/main/readme_images/step%207%20type%20info%20as%20prompted.png)

Step 8: To save the available loans as a .csv file, type yes and hit the enter key. 
*note: if not saving the file, type no. If no loans are available, a message will print letting you know.*

![save](https://raw.githubusercontent.com/gtaraboletti/Module2_Challenge/main/readme_images/step%208%20type%20yes%20and%20hit%20enter%20.png)

Step 9: Find the saved .csv file in the same folder as the app.py file. Now you're done and can open your .csv file in Excel or another spreadsheet program!

![finalstep](https://raw.githubusercontent.com/gtaraboletti/Module2_Challenge/main/readme_images/step%209%20find%20csv%20file%20in%20directory%20where%20you%20ran%20app%20from.png)


---

## Contributors

Giselle Taraboletti 
UNCC FinTech Boot Camp

---

## License

MIT License

Copyright (c) [2021] [Giselle Taraboletti]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

