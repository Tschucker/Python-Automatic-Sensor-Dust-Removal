# Python-Automatic-Sensor-Dust-Removal
Python algorithm for automatically detecting and removing sensor dust from images

This project uses OpenCV to detect and remove spots on your images that were caused by dust on the cameras sensor.

The full description of the algorithm can be found on my blog post below.

[Tea and Tech Time: Automatic Sensor Dust Removal](https://teaandtechtime.com/automatic-sensor-dust-removal/)

## Algorithm Output Images

Original Image

![](output_images/original_image.png)

Thresholded and Amplification

![](output_images/comb_threshold.png)

Detected Dust

![](output_images/shape_detect.png)

Cleaned Image

![](output_images/auto_dust_inpainting.png)