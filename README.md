# Computer-Vision

The facial recognition model is divided into two scripts
- enroll.py registers faces using Insightface, into Pandas dataframes. Using facial embeddings extracted from the images, they are enrolled into a database.
- search.py matches the query images or videos to already enrolled ones.


Unattended object detection uses a Ultralytics YOLO model and Roboflow. It implements ByteTrack to identify objects being left by people.
