# radModels
Radiance models containing rad files and view files.

#### Instructions for using the files.  
Each directory contains a separate radiance model.  
Within each directory, you will find a .rad file called model.rad. This is the main model file.  
model.rad links to scene materials and geometry through a series of `xform` commands.  
Some of the project directories contain view defintions in the views sub-directory.  
The view defintions can be used through the `-vf` flag in `rpict`, `rvu` etc. 

