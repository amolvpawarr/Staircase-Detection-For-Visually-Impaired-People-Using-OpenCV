# Staircase-Detection-For-Visually-Impaired-People-Using-OpenCV

According WHO fact sheets 285 million people were estimated to be visually impaired           worldwide: 39 million were blind and 246 have low vision. These people faces many problems while navigating and one of problem is Staircase navigation.

In this Project our approach is by using some cv techniques to detect the stairscase and alert user by audio output.

Approch:
Since stairs structure consists of stair lines in parallel so have used canny edge detector and hough transform to extract the lines from image. Canny edge detection clears the noise and smooths the image and thus lines will be identified by the hough transform.

So now we have lines in a image. But staircase have parallel lines and have sufficient length so,

Following are the key features of in detecting the staircase:

1. Lines should be enough long to be considered as a stairs
2. Lines should be parallel to each other
3. Not all lines should have same length
4. There should be at least 4-5 lines detected with above criteria
5. Image should be taken almost horizontal 
6. There should be some distance in 2 lines

by using GTTS(google text to speech) we get audio output.






