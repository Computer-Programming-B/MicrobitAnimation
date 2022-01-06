micro:bit Animation
--------------------
In this assignment you will program your own original animation using the micro:bit LED dispaly. Check the links at the bottom of this page for samples of student work. To code your animation you will use the functions `display.show()`, `Image()` and `sleep()`. Here's some sample code that makes a beating heart animation:
```python
from microbit import *

while True:
    display.show(Image( #Big Heart
        "09090:"
        "99999:"
        "99999:"
        "09990:"
        "00900"))
    sleep(500)
    display.show(Image( #Little Heart
        "00000:"
        "09090:"
        "09990:"
        "00900:"
        "00000"))
    sleep(500)
```
Each of the numbers 0 - 9 control the brightness of an LED on the display. 0 is fully off and 9 is fully lit. The `sleep()` function takes one argument that specifies how long in milliseconds the program will wait before it executes then next line of code. 1000 milliseconds is the same as 1 second.

You may find slides 1 - 34 of the [slide presentation](https://docs.google.com/presentation/d/1aiGcnPn8uoCJdX8p7_qoI3Hh3_KOhUtFeB3Byw0tacA/edit?usp=sharing) helpful in completing this assignment. If you are working at home, you can use the [microbit online simulator](https://create.withcode.uk/)   

Program requirements
-----------------
* Your program must use at least two original Images that you create 
* Your program must use the `sleep()` function to animate the images
* You will need to submit the Python code and video (see below) in the form of an animated gif showing your program running

Suggested steps to completing this assignment
----------
1. Create an animation that has at least two images you have created using [DIY images](https://microbit-micropython.readthedocs.io/en/v1.0.1/tutorials/images.html#diy-images)
2. Take a video of your animation running
3. Convert the video to an animated gif (see below and slides 26 - 32 of the [slide presentation](https://docs.google.com/presentation/d/1aiGcnPn8uoCJdX8p7_qoI3Hh3_KOhUtFeB3Byw0tacA/edit?usp=sharing)) that is smaller than 25Mb
4. Submit the video to google classroom
5. Submit the code to google classroom (see slides 31 - 33 of the [slide presentation](https://docs.google.com/presentation/d/1aiGcnPn8uoCJdX8p7_qoI3Hh3_KOhUtFeB3Byw0tacA/edit?usp=sharing))

Make a short video (under 10 seconds and smaller than 25MB)
-----------------------------------------------------------
When you are happy with your program, use your cellphone camera to make a short video of your program running on the micro:bit. The video need only show your micro:bit running, please don't include anyone's face in the video. See the samples of student work below for examples.   

Convert the video to an animated gif using a free converter like [ezgif.com](https://ezgif.com/). Use ezgif's *cut video* or a similar option to edit your video to under 10 seconds and less than 25MB. Submit your animated gif to Google Classroom. 

Samples of Student Work
----------
[Stephanie](StephanieLEDanimation.GIF)   
[Alyssa](AlyssaLEDanimation.GIF)   
[Justin](JustinLEDanimation.gif)   
[Kaitlyn](KaitlynLEDanimation.GIF)   
[Isaac](IsaccLEDanimation.GIF)      
[Calvin](CalvinLEDanimation.gif)   
[Jolina](JolinaLEDanimation.gif)   
[Thomas](ThomasLEDanimation.gif)   
[Margaux](MargauxLEDanimation.gif)   
[Yangyang](YangyangLEDanimation.gif)   
[Tennyson](TennysonLEDanimation.gif)   
[Allison](AllisonLEDanimation.gif)   
[Donovan](DonovanLEDanimation.gif)   
[Kathy](KathyLEDanimation.gif)    
[Douglas](DouglasLEDanimation.gif)   
[Joseph](JosephLEDanimation.gif)   
  

