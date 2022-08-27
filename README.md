# ToonTown Corporate Clash Auto Golf
This is a program that automates the golfing process in ToonTown Corporate Clash. The program will not work on ToonTown Rewritten, as it uses image recognition and pixel location for clicks/movement. The program does not inject code into ToonTown; it analyzes the user's screen for pre-taken screenshots (located in a folder within the program) and then simulates mouse movement/clicks and keyboard movement.

# Execution
Program is controlled with a GUI that will appear when the exe file has been opened. When the start button is clicked, the GUI will notify the user the program has started and the Auto-Golfer will begin. To stop the program, simply click the stop button located on the GUI.  More detailed instructions for usage and setup are included in the [INSTRUCTIONS](https://github.com/floopergobber/ToonTown-Corporate-Clash-Auto-Golf/wiki/INSTRUCTIONS) page.

GUI Image 1

![Auto Golf GUI IMG1](https://user-images.githubusercontent.com/111534019/185483895-acabbc55-d6de-485e-b868-4c60921c76fb.png)

GUI Image 2

![SQapZ11LDW](https://user-images.githubusercontent.com/111534019/185484138-5a0bdcd2-a926-4bc1-aa84-bf436a694226.png)

#Development/Additional Details
The program's image identification is not 100 percent accurate; sometimes it will fail to recognize a course image and the golfing will time out. This is not a problem, as multiple fail safes are built in to prevent the program from ever completely failing. If the golf times out, your character will resume searching for spawn images and run to the golf cart. If the toon cannot find any spawn images after 20 seconds, he will open the schticker book and return to the playground to resume searching for the spawn image. The program is designed to be run overnight or whenever you have a fair bit of time you will be away from the computer. It will max golfing relatively fast; I have maxed 3 different accounts with it in the testing process of the program. I am aware the program is not 100% efficient or as well written as it could possibly be. The file is fairly large: I used cx_Freeze to package the dependencies and images into one file so that the user does not have to install python or anything else. If you have any bugs/issues/criticisms please feel free to post them.


