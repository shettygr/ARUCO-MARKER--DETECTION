# ARUCO-MARKER--DETECTION
This Python script uses OpenCV and ArUco library to detect ArUco markers in real-time using your RPI camera. It draws bounding boxes around the detected markers and displays their corresponding labels on the video feed.
# Working
1. The code uses the OpenCV library to detect ArUco markers in a video stream. ArUco markers are square markers with a unique pattern that can be used for various      computer vision applications.
2. The code initializes the ArUco dictionary and detector parameters. It also sets up a video capture object to read frames from the camera.
3. The code defines a list of marker IDs and corresponding labels. These IDs and labels are used to identify and label specific ArUco markers in the video stream.
4. The code enters a loop where it continuously reads frames from the camera and detects ArUco markers in each frame. If a marker with a matching ID is found, it       draws the marker on the frame and displays the corresponding label near the marker.
5. The code keeps track of the current marker index and the elapsed time since the last marker detection. After a certain display time, it moves on to the next         marker in the list. The loop continues until all markers have been detected or the user presses the 'h' key to exit.
# Output
