# NEU_XAI

This repo contains keras implementation of few XAI algorithms on NEU surface defect dataset.

*Training a MobileNet model on the NEU surface defect dataset using Transfer Learning, and visualizing the important features of test images using model agnostic LIME and SHAP algorithms.*

| ![Sample images from NEU dataset](https://github.com/smahesh2694/NEU_XAI/blob/master/NEU_dataset%20image.jpeg?raw=true) |
|:--:| 
| *Sample images from NEU dataset* |

1. NEU steel surface defect database --> Original 1800 image dataset

2. NEU steel surface defect database - Test Split --> contains 180 test images with 10% partition

3. xai_tl.ipynb --> Transfer Learning Mobile Net, fine tune, save model, prediction on test images, classification report, accuracy

4. xai_predict.ipynb --> load saved model, predict an input image from test set, import and apply LIME visual explanations
