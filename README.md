# BiomedicalOpticsExpress
Script for simplified movements of motorized STANDA linear stage

This is a script for “SPiiPlusMMI Application Studio” in a .mmf format. 
This script is mean to simplified software control movement of the motorized linear stage 8MTL1401-300-LEn1-100 (STANDA, Vilnius, Lithuania).

HOW TO USE:

Open the “SPiiPlusMMI Application Studio” software and connect it to the linear stage to control it via computer. 
Click on “Enable motors” and digit “COMMUT (0)” in the dialog box. 

![Capture3](https://user-images.githubusercontent.com/96936724/147923158-ecf10be0-9651-4bb5-97a5-20d0bff08a12.PNG)

Import the “Real move” motion manager file (.mmf) script.

This is the interface that will appear in your motion manager:

![Capture4](https://user-images.githubusercontent.com/96936724/147923175-cdfef83c-3aff-4463-a4cf-b76d37a78913.PNG)

In the "Move by" field digit the distance you want your stage to travel (unit is in cm). Click on "+/-" blue button to move the stage in the forward or backward direction respectively. Click on "Start Motion" to start the stage movement. Click on "Stop Motion" to stop the stage movement while it is travelling.   
In the "Feedback" field, click on "0" button  to set the current position to your "zero" position. 
In the "Parameters" panel, modify the parameters for stage movement by adjusting the values in the "Velocity", "Acceleration" and "Decelaration" field.
