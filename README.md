
Motion Detection using OpenCV

Motion detection is a fundamental task in computer vision that involves identifying changes in the position of objects within a video stream or image sequence. OpenCV provides a robust and efficient way to detect motion using various techniques.

Approach:

1. Background Subtraction: This method involves subtracting the current frame from a reference background image to detect moving objects.
2. Frame Differencing: This method involves subtracting consecutive frames to detect motion.
3. Optical Flow: This method involves tracking the motion of pixels or features between frames.

OpenCV Functions:

1. cv2.absdiff(): Computes the absolute difference between two images.
2. cv2.threshold(): Applies thresholding to segment out moving objects.
3. cv2.findContours(): Finds contours of moving objects.
4. cv2.drawContours(): Draws contours of moving objects.
5. cv2.calcOpticalFlowFarneback(): Computes optical flow.

The  code given in another file captures video, applies background subtraction, thresholding, and contour detection to identify moving objects.
