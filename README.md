# KWG2024
A 2D grasping RGB-D dataset for kitchen waste sorting scenarios
# Introduction
This dataset comprises original images captured with Kinect V2 and Realsense D455 cameras. The data includes 10 common types of sorting objects in kitchen waste scenarios, namely Plastic Bottle, Plastic Box, Paper Box, Paper Cup, Metal Bottle, Glass Bottle, Ceramic Cup, Wooden Block, Foam, and Others. This dataset include 2,167 RGB-D images taken against a relatively clean background and 949 RGB-D images against a dirty and complex background. The former are captured with the Kinect V2 camera, while the latter with the Realsense D455 camera. Moreover, calibration is performed on both cameras, utilizing the derived parameters to reduce image distortion and to align the RGB images with the depth images. Besides, the dataset comprises 2,721 assisted annotations and 18,059 human-experience annotated grasps based on the annotation standard of the [Cornell dataset](http://pr.cs.cornell.edu/grasping/rect_data/data.php).

![2444_aligned_color](https://github.com/user-attachments/assets/cdfd6d6f-fdd2-44ff-80c6-3f43d46b3bc2)
![2444](https://github.com/user-attachments/assets/ac674f6a-fa16-41d2-b278-b22ff0ef7984)
# Annotation
Our annotation tool used is adapted from the [grasp-rectangle-labelling tool](https://github.com/ulaval-damas/grasp-rectangle-labelling). Our tool can simultaneously annotate the standard annotations of the Cornell dataset and our customized assisted annotations.
# Attention!
Since our papers related to this dataset are currently under peer review, we are temporarily releasing only a subset of the dataset.

