## Image-compression-based-classification
The project’s major goal is to create a micro-drilling vision-based parametric evaluation scheme.
* We used different segmentation algorithms to segment and classify the parts of images.
* These segmentation algorithms are Mask-RCNN and UNET.

### Mask-RCNN
We provide a system for object instance segmentation. Our method recognises objects in an image while also producing a high-quality segmentation mask for each one. Faster-RCNN is extended by Mask-RCNN, which adds a branch for predicting an object mask in parallel to the existing branch for bounding box indentification. Mask-RCNN is easy to learn and only adds a minor overhead to Faster-RCNN.

We trained the Mask-RCNN model for 600 epochs on 700 images.
After testing the images
