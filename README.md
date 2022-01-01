# BiomedicalOpticsExpress
Script for simplified movements of motorized STANDA linear stage

This is a script for “SPiiPlusMMI Application Studio” software (.mmf file) for movement of the software controlled motorized linear stage 8MTL1401-300-LEn1-100 (STANDA, Vilnius, Lithuania).

HOW TO USE:
Open the “SPiiPlusMMI Application Studio” software and connect it to the linear stage to control it via computer. 
Click on “Enable motors” and digit “COMMUT (0)” in the dialog box. Import the “Real move” motion manager file (.mmf) script.

This is the interface that will appear in your motion manager:

![image](https://user-images.githubusercontent.com/96936724/147846829-290bcb46-6e41-402e-b887-43ce546d0c98.png)

In the "Move by" field digit the distance you want your stage to travel (unit is in cm). Click on "+/-" blue button to move the stage in the forward or backward direction respectively. Click on "Start Motion" to start the stage movement. Click on "Stop Motion" to stop the stage movement while it is travelling.   
In the "Feedback" field, click on "0" button  to set the current position to your "zero" position. 
In the "Parameters" panel, modify the parameters for stage movement by adjusting the values in the "Velocity", "Acceleration" and "Decelaration" field.
