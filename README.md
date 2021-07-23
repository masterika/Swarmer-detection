# Swarmer-detection

Phase contrast microscopy is favored by biologists because it translates the optical density variation between objects and surroundings into signal thus making largely transparent structures for simple brightfield microscophy more visible. It is therefore well suited for studying small objects like cells.

One can look at density, size, velocity and ect. variations of cells to understand their behaviour deeper. However, tracking them mechanically is a tedious job and phase contrast microscopy images are notoriously difficult to segment by conventional computer algorithms due to low contrast. 

Here I use mask-rcnn (citation below) to detect swarming bacteria in phase contrast microscopy images. You can view and reproduce results in "Swarming_bacteria_detection_with_Mask_R_CNN.ipynb" file. You can also easily train your own dataset using that code. Below, on the left I display a typical picture from the test set, and on the right you can see how well the program detects bacteria.

![original](https://user-images.githubusercontent.com/7634351/126841434-0a7cd053-1b84-4f00-a5cf-cbf3bb2c1ea3.png)
![original 2](https://user-images.githubusercontent.com/7634351/126841539-c1543095-f73c-4d86-8a40-7d437e1930ce.png)


@misc{matterport_maskrcnn_2017,
  title={Mask R-CNN for object detection and instance segmentation on Keras and TensorFlow},
  author={Waleed Abdulla},
  year={2017},
  publisher={Github},
  journal={GitHub repository},
  howpublished={\url{https://github.com/matterport/Mask_RCNN}},
}
