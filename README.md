On Screen Keyboard
==================

# Notes For The Reviewer

- This is my first time using C# in a project ever.
- I chose to use C# since it fits into the .NET framework very well.
- To run my program:
	- Open solution file in Visual Studio Code.
	- Start the OnScreenKeyboard file.
- My program assumes a user wants to select a text file to read with a GUI display and has a text file ready to select.
- My program outputs to the console, but this output is a string that could be returned anywhere in the software.
- My code is the following:
	- OnScreenKeyboard.cs
	- KeyboardConverter.cs
	- KeyboardMapping.cs
	- All other code is part of the VS Code generation that allows the program to run


The Problem
-----------
On screen keyboards are the bane of DVR users. To help alleviate the pain, one local company is asking you to implement part of a voice to text search for their DVR by developing an algorithm to script the on screen keyboard.
The keyboard is laid out as follows:

```
ABCDEF
GHIJKL
MNOPQR
STUVWX
YZ1234
567890
```

Please write a program which scripts the path of the cursor on the keyboard. The program should: 

1. Accept a flat file as input.
	1. Each new line will contain a search term
2. Output the path for the DVR to execute for each line
	1. Assume the cursor will always start on the A
	2. Use the following characters to make up the path
		1. U = up
		2. D = down
		3. L = left
		4. R = right
		5. S = space
		6. \# = select
3.	Comma delimit the result

Sample Input
------------
IT Crowd

Sample Output
-------------
D,R,R,#,D,D,L,#,S,U,U,U,R,#,D,D,R,R,R,#,L,L,L,#,D,R,R,#,U,U,U,L,#

The Fine Print
--------------
Please use whatever techniques you feel are applicable to solve the problem. We suggest that you approach this exercise as if this code was part of a larger system. The end result should be representative of your abilities and style.  We prefer that you submit your solution in a language targeting the .NET Framework to help us better evaluate your code. 

Please fork this repository. If your solution involves code auto generated by a development tool, please commit it separately from your own work.  When you have completed your solution, please issue a pull request to notify us that you are ready.

Have fun.
