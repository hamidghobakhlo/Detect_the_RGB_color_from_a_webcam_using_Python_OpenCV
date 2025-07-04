# Dominant Color Detection Using Webcam

Every image is represented by 3 colors that are Red, Green and Blue. Let us see how to find the most dominant color captured by the webcam using Python.

## Approach:

- Import the cv2 and NumPy modules  
- Capture the webcam video using the `cv2.VideoCapture(0)` method  
- Display the current frame using the `cv2.imshow()` method  
- Run a while loop and take the current frame using the `read()` method  
- Take the red, blue and green elements and store them in a list  
- Compute the average of each list  
- Whichever average has the greatest value, display that color


## Output:
![Dominant Color Output](images/sample_output.jpg)

## Resualt:
![Dominant Color Output](images/resualt.jpg)