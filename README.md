## Image-compression-based-classification
The project’s major goal is to create a micro-drilling vision-based parametric evaluation scheme.
* We used different segmentation algorithms to segment and classify the parts of images.
* First we had to collect the data and annotate the data in order to perform segmentation and classification
* These segmentation algorithms that we use are Mask-RCNN and UNET.

### Mask-RCNN
We provide a system for object instance segmentation. Our method recognises objects in an image while also producing a high-quality segmentation mask for each one. Faster-RCNN is extended by Mask-RCNN, which adds a branch for predicting an object mask in parallel to the existing branch for bounding box indentification. Mask-RCNN is easy to learn and only adds a minor overhead to Faster-RCNN.

![Mask-RCNN block diagram](https://github.com/vinodindi8701/Image-compression-based-classification/blob/main/Mask%20RCNN/Block%20diagram/final.png)

### Project block diagram
![Project block diagram](https://github.com/vinodindi8701/Image-compression-based-classification/blob/main/Mask%20RCNN/Block%20diagram/fb.jpg)

We trained the Mask-RCNN model for 600 epochs on 700 images.
After testing the trained model on 200 images we got mAP of 0.33366.

### Results:
![Result 1](https://github.com/vinodindi8701/Image-compression-based-classification/blob/main/Mask%20RCNN/Mask%20predictions/test%201.png)

![Result 2](https://github.com/vinodindi8701/Image-compression-based-classification/blob/main/Mask%20RCNN/Mask%20predictions/test9.png)
