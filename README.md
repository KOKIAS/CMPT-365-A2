CMPT 365 Programming Assignment 2 
 
Objective :  
To mastery the fundamentals of multimedia manipulation (using libraries of OpenCV) and user interface design 
 
Background :  
The application is a video-based program to help blind people. By using the sense of hearing, the application can help our brain to construct a (gamma-corrected) grey image, used the loudness to represents the intensity of the color, and used the frequency to represent the location of the pixels. 
 
Libraries : 
In the assignment we used: 
 	1.OpenCV for the video 
 	2.JavaFX for the GUI  
 	3.Java Sound API for the sound 
 
Video : 
In the given skeleton code, The application can play an image ( with sound) and a video. We modified the open image function, it can detect the type of selected file. If file is a video, the application will use the helper function to create frame grabber and divide the video into different frames. These frames will be processed as images and use as inputs for the play image function. 
 
Sound :  
The one signal for the sound to be created when it “play” the image. We have to modify it. Hence, another signal of sound will play a click sound for every 2 frame. 
![image](https://github.com/KOKIAS/CMPT-365-A2/blob/master/1.jpg?raw=true)
 
 
GUI : 
The application can only load the one given image, and it only has two buttons on the pop up window. We modified it. Therefore, the users can chose their own file to be played and the program also has an extra button, the stop “button” is for stopping the application.

![image](https://github.com/KOKIAS/CMPT-365-A2/blob/master/image.png?raw=true)

The application uses the JFileChooser to allows users to chose the file what they want to play. 
![image](https://github.com/KOKIAS/CMPT-365-A2/blob/master/2.jpg?raw=true)
