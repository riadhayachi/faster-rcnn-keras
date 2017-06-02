# keras-frcnn with object counting example

This is a fork of the oryginal keras-frcnn example modified to display the count of detected images (grouped by class). It allows processing videos (not in real time though)

Keras implementation of Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks.

Description of this simple project can be found at [Softwaremill Blog](http://www.softwaremill.com/counting-objects-with-faster-rcnn)

Example of processed video:

<iframe width="560" height="315" src="https://www.youtube.com/embed/z2wQBNDYRXg" frameborder="0" allowfullscreen></iframe>

Usage:

Script arguments are rather self explanatory:

- "--input_file", Path to input video file.
- "--output_file", Path to output video file.
- "--input_dir", Path to input working directory where the processed frames are stored
- "--output_dir" Path to output working directory where annotated processed frames are stored
- "--frame_rate" Frame rate to use while constructing the video output

Example usage:

```bash
python test_frcnn2.py --input_file ~/videos/MVI_6848.mp4 --output_file ~/output4.mp4 --frame_rate=25
```

For usage in training please see the oryginal project GitHub page. 