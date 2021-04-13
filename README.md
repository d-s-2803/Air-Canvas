# Air-Canvas

1. Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection)
2. Prepare the canvas frame and put the respective ink buttons on it. 3.. Adjust the trackbar values for finding the mask of coloured marker.
3. Preprocess the mask with morphological operations.(Erotion and dilation)
4. Detect the contours, find the center coordinates of largest contour and keep storing them in the array for successive frames .(Arrays for drawing points on canvas)
5. Finally draw the points stored in array on the frames and canvas .

Requirements: python3 , numpy , opencv installed on your system.

Credits to Youtube Video : https://www.youtube.com/watch?v=eHgvMAwfODw
