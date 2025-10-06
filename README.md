🦴 Lumbar Spine Degenerative Classification using YOLOv11 📌 Project Overview This project focuses on classifying degenerative conditions of the lumbar spine using the YOLOv11 model. The dataset was obtained from Roboflow in TensorFlow format. The model detects and classifies spinal conditions, aiding in automated medical diagnosis.

📂 Dataset Source: # Augmented_dataset > 2024-11-17 8:55am https://universe.roboflow.com/dl-ljbpi/augmented_dataset-cckeg

** Provided by a Roboflow user License: CC BY 4.0 Augmented_dataset - v1 2024-11-17 8:55am **
This dataset was exported via roboflow.com on November 18, 2024 at 1:22 PM GMT

Roboflow is an end-to-end computer vision platform that helps you

- collaborate with your team on computer vision projects
- collect & organize images
- understand and search unstructured image data
- annotate, and create datasets
- export, train, and deploy computer vision models
- use active learning to improve your dataset over time
  
For state of the art Computer Vision training notebooks you can use with this dataset, visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 2342 images. Spinal-canal-stenosis are annotated in Tensorflow TFRecord (raccoon) format.

The following pre-processing was applied to each image:

The following augmentation was applied to create 2 versions of each source image:

- 50% probability of horizontal flip
  
The following transformations were applied to the bounding boxes of each image:

- Randomly crop between 0 and 43 percent of the bounding box Format: TensorFlow (TFRecords) Contains: Annotated lumbar spine images with labeled degenerative conditions. 📊 Results The model achieves high accuracy in classifying lumbar spine conditions. Uses real-time object detection for medical imaging. Supports bounding box annotations for better interpretability. 🚀 Future Improvements Enhance model performance with hyperparameter tuning. Expand the dataset for better generalization. Implement Grad-CAM for explainability in medical AI.
