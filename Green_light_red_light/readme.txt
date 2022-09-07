In order to practice cv2 image and video handling I've written a script for teh green light red light game inspired from the Squid game serie.
The script opens a stream of a connected camera and catchs any element moving while filming.At the end a video will be saved in the diretry next to the script file. 

make sure to install the dependencies before you run the code :
pip install opencv-python 
pip install numpy 

before you run the game.py code you have to also make sure that you have a connected camera. Inside the code you have to choose  the source of stream let  0 for your pc camera and 1 ..2..3.. for any other sources . you can actually provide an already saved video in the capture by given the path as a parameter.

Key features : after you start the window you have three control inputs from the keyboard.  r:for red light and it starts catching teh movement and drowing green boxs on the moving elements , g : for green light and it stop tracing , f: for finish and it closes the window and saves the record .
The motiontrack.py file contains the basic code for tracking without keys features .

I hope you like  the concept and enjoy trying to run game on your computer .
After all this code not just for fun but it could be used in many real time Ai projects.
Thank you for reading
