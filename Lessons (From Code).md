**What We Learned from the Coding (From Test (Base) Code)**

*Adding Images to Game (Code):*
We have first received this code with the help of Ms.Luce but unfortunately could not tune the coding to be suitable for our game.
The code ended up covering up the entire screen with an image, thus making it almost impossible for the player to play the game (due
to the lack of vision of the actual bricks and paddle). From the coding, we have learned how to include an image into the game by turning
the image into an object (JLabel) and inserting it into the game by attaching it into a JFrame. The image can be adjusted by changing the
dimensions of the JFrame and can be visible by using a simple setVisible method. The JFrame.EXIT_ON_CLOSE (with the default close operation code at the top)
also exits the application when the player wants to exit the game as well (unlike the other default close operations availible). 

*Adding Audio to the Game (Soundeffect to be more specific):*
We have figured out how to implement this piece of coding by watching around two videos (in which one was significantly more useful than the other).
The first small detail that we learned while watching the video and using the code is the usage of "Exception ex" instead of the standard "Exception e". 
This small change actually allows us to use the "ex.printStackTrace();" which prints out the actual entire error message. This makes debugging the code
much easier. The first piece of this code is creating a file object (shown in the code). The "musicLocation" is the string that we pass through the playMusic
method in the main class. (import java.io.File is also needed but was not included in the base code) We then create a small if statement, shown in the code, to check whether the file (music audio) actually exists within the game files (also needs two other imports which are AudioInputStream and AudioSystem classes). Now that we have figured out (or in better terms, the code has figured out) that the file actually exists, we create another small line of code that takes the audio file and inputs it into the game/project. This code is found in the "if musicPath exists" section. When then use the Clip class (also imported) and clip object to actually obtain the Audio stream from the audioInput object (in
the base code). Then we write a line of code to actually open the audio clip (Clip.open(audioInput);). After this is done we go to our main class and make/type a line of code to reference our previous class (which also includes our method to play the music) by creating an instance (ie. musicPath musicObject = new musicStuff();). Then after that we write "String filepath = "audio.wav" to actually use the audio file we want to play (this step is before the instance part, and the audio.wav is a placeholder for the audio clip). Then we create a line of code which play the file we want with the usage of the method we created in the previous class (ie. musicObject.playMusic(filepath);) In the original code the person used an X-Button or escape panel as an interruptor but we altered that to suit our game. 

Generally Speaking: We learned how to include soundeffects into our game with several different techniques such as creating instances, importing classes, referencing and more. 


