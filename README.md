# Site
MiorSoft [web pages](https://miorsoft.github.io/Site/index.html)

## PhotoModularFX
**PhotoModularFX** is a project about image manipulation performed by custom effects flow.  
It's PORTABLE (No installation needed)  

[Webpage](https://miorsoft.github.io/Site/PhotoModularFX/index.html)  
[Download](https://miorsoft.github.io/Site/PhotoModularFX/PhotoModularFX.zip)  

For any kind of feedback feel free to write in the [FORUM](https://github.com/miorsoft/Site/discussions)
  
This project was born with the intention of creating an unconventional image editor.  
It is full of image processing software, and, I really did not care to create one like many others.  
The intent was to create a program that gave the user the ability to create and customize the graphic effect.  
In fact, the beauty of this program is that the image processing process consists of a series of modules that can be assembled as desired to create the desired effect.  
In fact, this project was also born to simplify the creation of the "Cartoonize" effect to myself. (instead of having to fight modifying the code, I just had to use the mouse and connect and set module parameters)
This process consists of a flow of information that runs through the different modules.  
Each of these modules performs a different transformation operation on the data.  
Each module has its inputs and outputs consisting of 2D arrays.  
The node to load the image can be "INPUT" for the use of 3 channels (RGB) or "INPUTA" for the use of 4 channels (RGBA)  
The range of the initial RGB values ​​are transformed from 0-255 (integer) to 0-1 (float).  
Since the modules are in cascade this remapping range allows a more precise final result. (a sort of continuous vs discreet)  
In general, the outputs of the modules also have a range of 0-1, even if this is not always true, some modules can output negative ​​or greater than 1 values.  
At the end of the flow it is always necessary to place an output module. This can be "OUTPUT" which corresponds to "save as JPG" or "PNGout" which corresponds to "Save as PNG"  
Obviously these modules transform their inputs from the 0-1 range to the 0-255 range.  
  
Now more than three years have passed since the beginning of this project.  
I made steps and added many interesting features.  
This happened a little at a time, in small steps. As a new idea appeared to me, I tried to implement it. (you can take a look at [History](https://github.com/miorsoft/Site/blob/master/PhotoModularFX/History.txt))

Test page ..... more to come
