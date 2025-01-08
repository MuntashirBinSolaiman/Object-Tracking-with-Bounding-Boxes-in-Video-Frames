# Object-Tracking-with-Bounding-Boxes-in-Video-Frames

What:
This project performs object tracking in video frames, identifying and following objects of specific classes across consecutive frames. It associates bounding boxes with corresponding objects and visualizes their movements over time in a video with annotated class labels.

How:
Bounding Box Detection: Bounding boxes are provided for each frame, along with class labels for detected objects.
Object Association: Objects are tracked by comparing the center distances of bounding boxes across frames, ensuring the same object is linked.
Visualization: A unique color and class label are assigned to each tracked object, drawn on the video as rectangles and text annotations.
Output Video Creation: The annotated frames are compiled into a video showcasing the tracking results.
Why:
Object tracking is crucial for understanding object behavior and movement in video analysis tasks such as surveillance, autonomous driving, and sports analytics. This project demonstrates a simple yet effective approach to tracking objects using class labels and spatial proximity.
