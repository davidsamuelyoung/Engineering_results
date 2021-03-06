# Read this before getting the program for the first time (or when updating the program)

Current version: v1.09 (Gooey Marks)

Required Python version: v3.6+

See below for required packages* (only required for screens below 1080p)

To get this program follow this:

https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository

Or just click download zip (from the green button called "Code").

#### If you are downloading Engineering_results for the first time follow the steps below:
1. Rename results_example.txt to results.txt (or duplicate results_example.txt and then rename)
1. Open Command Prompt or Terminal
3. Navigate to the directory where you have downloaded the Engineering_results file
4. Run the following code next: "python3 results.py"
5. Enter your marks into the respective courses (in decimal or quotient format -- i.e. 0.96 or 24/25 -- 
if you only have percentages, divide the value by 100)

#### If you are coming from v0.0x follow the steps below:

1. Open Command Prompt or Terminal
2. Navigate to the directory where you have downloaded the Engineering_results file
3. Run the following code: "python3 make_results_file.py" (you must only run this program once)
4. Run the following code next: "python3 results.py"
5. Enter your marks into the respective courses 
(in decimal or quotient format -- i.e. 0.96 or 24/25 -- if you only have percentages, divide the value by 100)

You will have to re-run the results.py program if you want to see the marks in the "Current Marks for semester" screen.

#### If you are coming from v1.0x follow the steps below:

1. Open Command Prompt or Terminal
2. Navigate to the directory where you have downloaded the Engineering_results file
3. Run the following code: "python3 EditMarks.py" (you should only run this program once)
4. Run the following code next: "python3 results.py"
5. Enter your marks into the respective courses 
(in decimal or quotient format -- i.e. 0.96 or 24/25 -- if you only have percentages, divide the value by 100)

You will have to re-run the results.py program if you want to see the marks in the "Current Marks for semester" screen.

#### Users on computers with screen resolution below 1080p

1. Open Command Prompt or Terminal
2. Run "pip3 install pyautogui"
3. Use the Mark Calculator like normal

## Keeping your program up-to-date: How-to
Download the latest version of the results.py and replace the current file in your directory with the latest 
versions.

(Make sure that results.txt is in the same directory as the new results.py otherwise it'll break)

Run the program.