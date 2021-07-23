# Swarmer-detection

Phase contrast microscopy is favored by biologists because it translates the optical density variation between objects and surroundings into signal thus making largely transparent structures for simple brightfield microscophy more visible. It is therefore well suited for studying small objects like cells.

One can look at density, size, velocity and ect. variations of cells to understand their behaviour deeper. However, tracking them mechanically is a tedious job and phase contrast microscopy images are notoriously difficult to segment by conventional computer algorithms due to low contrast. 

Here I use mask-rcnn (citation below) to detect swarming bacteria in phase contrast microscopy images. You can view and reproduce results in "Swarming_bacteria_detection_with_Mask_R_CNN.ipynb" file. You can also easily train your own dataset using that code.
![original](https://user-images.githubusercontent.com/7634351/126838874-f518bdbb-b0a8-4c32-9624-4a34414134b9.png)
![processed](https://user-images.githubusercontent.com/7634351/126838879-2049be68-38af-4298-99a7-442165f83e3c.png)

@misc{matterport_maskrcnn_2017,
  title={Mask R-CNN for object detection and instance segmentation on Keras and TensorFlow},
  author={Waleed Abdulla},
  year={2017},
  publisher={Github},
  journal={GitHub repository},
  howpublished={\url{https://github.com/matterport/Mask_RCNN}},
}
