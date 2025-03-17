# Air-canvas
This would be my first project on python opencv
Description about the project work:  
The Air Canvas project aims to create a virtual canvas where users can draw in the air using 
their hand movements. By leveraging computer vision techniques, the project tracks the user's 
hand movements and translates these into drawing commands, allowing for real-time 
interaction without the need for physical contact with a drawing surface. 
Key Components 
1. Hand Detection and Tracking: The system uses a camera to capture video frames and 
detect the user's hand in real-time. 
2. Gesture Recognition: Specific hand gestures are recognized to distinguish between 
different drawing actions (e.g., drawing, erasing). 
3. Drawing on Canvas: The detected hand movements are translated into drawing 
commands on a virtual canvas. 
Algorithm:  
1. Start reading the frames and convert the captured frames to HSV color space (Easy for 
color detection).  
2. Prepare the canvas frame and put the respective ink buttons on it.  
3. Adjust the track bar values for finding the mask of the colored marker.  
4. Preprocess the mask with morphological operations (Eroding and dilation).  
5. Detect the contours, find the center coordinates of largest contour and keep storing them 
in the array for successive frames (Arrays for drawing points on canvas)
