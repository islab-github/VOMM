# VOMM: Vision Objects for Mobility Management 

![](fig_VOMM-1.png)

VOMM is a vision dataset specially designed for the evaluation of the deep learning (DL)-based object detection performance in terahertz (THz) ultra-dense network (UDN) scenarios.
It consists of 232 pairs of RGB and depth images acquired at the viewpoint of multiple SBSs.


## Preparation
Please download the VOMM dataset from https://www.dropbox.com/scl/fo/p5bbr2x6ka2z3xly4a9v5/h?rlkey=tt22bbc095vxlcu8savk595p0&dl=0.

In VOMM, we store the images and corresponding labels in two different folders named ‘image’ and ‘label’, respectively. To be specific, in the ‘image’ folder, there are three subfolders named ‘rgb’, ‘depth’, and ‘distance’. The ‘rgb’ subfolder contains RGB images, while the ‘depth’ subfolder contains corresponding depth images. In the ‘distance’ subfolder, the distance to the point in each pixel is included. This information is available in JSON format. On the other hand, the ‘label’ folder provides labels for images of VOMM in XML format. Each label includes the width, height, and depth of the image, as well as objects labeled with one of the three classes and their bounding box coordinates. Specifically, persons are labeled as ‘person’ and cell phones as ‘P’.
