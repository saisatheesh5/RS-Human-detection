# Realsense Human Detection
> Human detection, person count and distance measurement with Realsense Depth Camera

## Components used
Human detection: MobileNet SSD model
Tracking: Centroid tracker
Distance Measurement: Realsense depth data

## Python requirements:
* Python Version >3.7
* pyrealsense2
* NumPy
* OpenCV
* imutils
* scipy
* collections



## Running:
use the command `python3 rs_human_detection.py` to run the program.

The following actions take place when running the program
1. real-time frames captured by the camera are displayed.
2. bounding boxes is added for human along with the distance of the person from the camera.
3. Unique ID is assigned for each person which is also displayed.
4. The total count of people in the frame and the count of people from the beginning of program execution are displayed.
5. Video recording is saved in the path specified in the program.

**Limitations:**
This program works only for Realsense cameras with depth features. It has been tested with L515 and D435i.

## Result:
The output obtained from this program can be viewed in the [Result folder](https://github.com/saisatheesh5/RS-Human-detection/tree/main/Result).
