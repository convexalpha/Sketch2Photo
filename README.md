# Sketch2Photo
An implementation of the paper sketch2photo for converting hand-drawn sketches to graphic images 

## Project Description
This is my implementation for the paper Sketch2Photo: Internet Image Montage. A simple freehand sketch is automatically converted into a photo-realistic picture by seamlessly composing multiple images discovered online. 

![Figure 1](figures/fig1.png)
*The input sketch plus overlaid text labels is shown in the figure along with a composed picture and some further compositions. Discovered online images used during composition are also shown*

## Pipeline
The input is a user-drawn sketch giving a text label for each scene item. We search the Internet for images matching the text labels and select discovered images with contents matching sketched contours; at the same time, each scene item is segmented. Then we optimally combine elements of the candidate images. Several compositions are generated from which the user may make a selection.

![Figure 2](figures/fig2.png)

## Results 
Composition results where image with a red frame is a failed example.

![Figure 2](figures/fig3.png)




(Note that this is a basic implementation of the paper's idea and doesn't contail all the functionalities of the same.)

