# Day and Night Classifier

[Computer Vision Nanodegree](https://www.udacity.com/course/computer-vision-nanodegree--nd891) 

## Overview
The Day and Night Classifier is a machine learning project developed by Udacity, designed to classify images as either "daytime" or "nighttime" scenes. This project aims to demonstrate the application of image classification techniques using a simple dataset of daytime and nighttime images.

## Dataset
The dataset consists of a collection of images captured during the daytime and nighttime. Each image is labeled as either "day" or "night" to indicate the time of day when the photo was taken. The dataset is preprocessed and split into training and test sets for model development and evaluation.All images come from the [AMOS dataset](http://cs.uky.edu/~jacobs/datasets/amos/) (Archive of Many Outdoor Scenes).

## Model
The classifier utilizes a basic brightness based classfier to extract features from input images and classify them into daytime or nighttime categories. The model gives eough basics on concepts such as masking, HSV image, understand of how change in value and saturation affects image brightness.

## Installation
1. Clone the repository
```bash
git clone https://github.com/your_username/day-night-classifier.git


```
2. Install Dependencies :
* OpenCv
* PyTorch
* NumPY

## Results
The performance of the Day and Night Classifier can be evaluated using metrics such as accuracy, precision, recall, and F1 score. The model's ability to correctly classify daytime and nighttime images is crucial for its practical applicability.

## Future Improvements
- Experiment with different CNN architectures and hyperparameters to improve classification accuracy.
- Incorporate data augmentation techniques to enhance model generalization.
- Explore transfer learning by fine-tuning pre-trained CNN models for improved performance.

## Contributors
- [Your Name](https://github.com/AchuthanKrishna)

## License
This project is licensed under the [MIT License](LICENSE).