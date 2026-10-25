You can use videos uploaded on CANVAS for real time obejct detection in Vision Lab2.
There are three objects shiwn in these videos.
single_objects.mp4 shows one obejct at a time. 
multiple_objects.mp4 shows two objects at a time.

NOTE that you SHOULD use ARUCO marker for converting pixel values to mm or cm.

Frames size: (2048, 2448)
fps: 20

The size of objects in mm:
Long block: 16x20
Square: 70x72
phone: 82x169

Some cases that might be problematic:
when the video ends and there are no frames left to read.
Sometimes, some part of the Aruco marker might be hidden behind other objects.

