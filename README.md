# Object 🚗 Tracking with DeepSORT

In this notebook, I combined the `YOLOv3` algorithm with the `DeepSORT` algorithm to create an `object tracking` module to track cars going on the road. This project uses YOLO to identify objects in each frame of the video and then uses the `DeepSORT` to keep track of each object in the video by giving it an `object ID` and then keeping track of the same object through the video using those object ID and `temporal references`.

# Dataset ⬇

The dataset used is the [`KITTI Vision`](https://www.cvlibs.net/datasets/kitti/) dataset

# Samples 📺📽

Samle tracking videos present in the `sample_video` directory, you need to `download` the videos in order to see the results.