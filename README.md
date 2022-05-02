# Computer Vision
Automated Labels-- Hard cut detection

# About
This is a tool to be able to detect hard cuts, or sharp transitions, within a clip. It requires an input of a folder of frames in a clip (the images in a sequence) and returns the number of hard cuts that are detected as well as the between which frames it appears.

# Inputs
The main cell in the ipynb file iterates through a folder of images and runs pairs of images through the feature matching function. This system requires a folder of frames taken from a clip, using a tool such as FFMPEG. 
