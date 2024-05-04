These are .3MF files that contain modified Pandora's Box and Pandora Gantry for use with a Box-Zero format printer. 

Things to note. Files are .3MF because exporting them as .STL doesn't keep the negative space objects (or I'm just doing it wrong). 
With that in mind make sure to switch back to your settings in the slicer.
Do not repair the files. For whatever reason with some of the files get repaired they don't print the interposed objects as a single part.
I have included the modified X carriage that I made for the Dragon Burner toolhead. I modified this one in CAD and thus it is an actual STL.

For the A and B drive's I follow the bearing stacks as set up in Pandora's Box instruction manual. One of the pictures uploaded shows how to deal with the outer bearing stacks on the Y extrusion as this is slightly different.

These would be considered proof of concept at this stage. They work, I have printed and installed them on my Tri-Zero, but they are far from perfect. 
I do plan to create better versions of them using CAD, but I am just starting out and it may take awhile or never happen.

Settings for your printer after install:

Y stepper endstop and position max should be 114 (Yes you lose 6mm of Y travel, remember proof of concept).
Y stepper position min should be 0.
X stepper endstop and position max should be 131.
X stepper position min should be -11 (this number might change depending on the toolhead being used).

I use Dragon Burner with Zero Click and for dock position use -6,114.

I use the stock Pandora's Box XY Joints.

There is possibly other stuff I forgot. Just message me on discord with any questions. @ax4xse7en (John).
