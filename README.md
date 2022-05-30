# Face-Filter-using-Face-Recognition
  ✨ This is a Web-based Application which insert filters on face.
  
  ## Web site Link -> https://geethikaaa.github.io/Face-Filter-using-Face-Recognition/
 ## Features:
    1. Inserting filters to face using face landmarks on home page.
    2. Taking snap of live webcam.
    3. Vedio recording
    4. Frames to canvas borders.
    5. Editing snap or any other photo on edit image web page.

## Requirements:

### Languages :
            
           ✨ HTML ✨
           ✨ CSS  ✨
          ✨ JAVA SCRIPT ✨
          
 ### libraries:
             ✨ P5.js ✨
            ✨ Clmtrackr ✨

## How it Works?
   
   > In P5.js in preload() function LoadImage() loads all the image filters required for the face.
   > Clmtrackr detects the face landmarks in order to insert the filters at correct position.


![](Images/clmtackr.png)


   >Intialisation of tracker:
   
    ✨ faceTracker = new clm.tracker();
     faceTracker.init();                          // This intialisation automatically connects face tracker to vedio input.
     faceTracker.start(videoInput.elt); ✨  
     
     
   > Then I inserted filters based on facial landmarks . They will look like this

     
  ![](Images/devilhorn.png)

   
  ![](Images/birthdayparty.png)
  
  >Like this using clmtrackr we can create any type of face filter.


## Designing Project using css and style.css:

  > I add some of the addtional features to project. For that I created another web page(edit image) to my project.
It looks like this-----


![](Images/editimage.png)
