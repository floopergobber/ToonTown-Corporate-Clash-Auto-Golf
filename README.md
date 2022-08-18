# ToonTown Corporate Clash Auto Golf
Automated Golf system for ToonTown Corporate Clash. Program will not work on ToonTown Rewritten, as it uses image recognition and pixel location for clicks/movement. The program does not inject code into ToonTown, rather it analyzes the user's screen for pre-taken screenshots (located in a folder within the program) and then simulates mouse movement/clicks and keyboard movement.

# Execution
Program is run via the exe file located inside the "MAIN" folder. Program does not require any additional downloads other than the "MAIN" folder and its contents. Program is run in Python and packaged with cx_Freeze for ease of use. Upon opening the .exe file, labeled [INSERT FINAL NAME HERE], a GUI (see first image below) will appear. When the start button is clicked, the GUI will notify the user the program has started and the Auto-Golfer will begin. To stop the program, simply click the stop button located on the GUI.  More detailed instructions for usage and setup are included in the INSTRUCTIONS section below.

GUI Image 1

![Auto Golf GUI IMG1](https://user-images.githubusercontent.com/111534019/185483895-acabbc55-d6de-485e-b868-4c60921c76fb.png)

GUI Image 2

![SQapZ11LDW](https://user-images.githubusercontent.com/111534019/185484138-5a0bdcd2-a926-4bc1-aa84-bf436a694226.png)

# INSTRUCTIONS
For the program to run properly, follow the list below.

1. Download the Auto Golfer ZIP file and open the archive/extract the files. (you can use whatever program you have to extract zip folders, ie. 7zip, winRAR, etc..) 
 
![step1](https://user-images.githubusercontent.com/111534019/185489452-87dad19b-830e-4da3-b0ff-981d6995e92c.png)

2. If you chose to open the archive, drag the Auto Golfer folder onto your desktop (or other desired location). If you extracted the contents, skip to step 3.
 
![step 2](https://user-images.githubusercontent.com/111534019/185489783-47f1649f-008e-4091-902b-1c1ad4c6ac07.png)

3. Open the Auto Golfer folder and open the Auto Golf.exe program.

![step3](https://user-images.githubusercontent.com/111534019/185490059-b47f8b1f-f1e2-4ab8-b9f4-a6e26edaecd4.png)

4. Click the Start button on the GUI to begin the Auto Golf program.
    NOTE: There are a few settings in Corporate Clash to tweak for the program to run properly.
    
      1: The Aspect Ratio MUST be set to 16:9 for the program to click the right locations and identify images properly. 
          
      2: Resolution MUST be set to 1600x900, as some of the click functions are set to pixel locations, and a different resolution will result in innaccurate/missed clicks.
          
      3: Schtickerbook size MUST be set to Large, same reason as #2 on the list.
          
      4: The rest of the settings should not matter, Anti-Aliasing, Antisotropic Filtering, FPS Meter, etc should have no effect on the program's accuracy.
              Note: I have tested the program with most of the settings changed, but have not experimented with Vertical Sync or Legacy Content Pack Support enabled. I have them disabled by default.
              
      5: You should click the start button once you have entered the Minigames Area Playground. The camera view MUST be on the furthest out setting while in spawn for the image recognition to properly work. You can easily change/reset the camera angle by pressing the TAB key. By default your Toon should load in with the camera angle the same every time. Simply press the TAB key twice to set the camera angle properly upon loading in. If the camera angle becomes altered, switch it back by pressing TAB until the camera angle is the farthest out again.
              
![InkedOptions1](https://user-images.githubusercontent.com/111534019/185491583-531a47eb-3b66-4d9a-801a-38cd3caa358d.jpg)
![InkedOptions2](https://user-images.githubusercontent.com/111534019/185491628-5c104bc2-b16f-4965-8247-600def076b72.jpg)

Correct Camera Angle:

![Correct Camera Angle](https://user-images.githubusercontent.com/111534019/185493984-c94469b8-fb44-4f55-8549-4273a648a52c.jpg)






