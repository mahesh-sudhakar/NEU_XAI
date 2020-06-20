# NEU_XAI

This repo contains keras implementation of few XAI algorithms on [NEU surface defect dataset.](http://faculty.neu.edu.cn/yunhyan/NEU_surface_defect_database.html)

Repo consists of :
<ol>
  <li>NEU steel surface defect database --> Original 1800 image NEU dataset</li>
  <li>NEU steel surface defect database - Test Split --> contains 180 test images (with 10% partition)</li>
  <li>Finetune_on_NEU_dataset.ipynb --> 
    i) Training a MobileNet model on the NEU surface defect dataset using Transfer Learning.
    ii) visualizing the important features of test images using model agnostic LIME and SHAP algorithms.</li>
</ol>

Sample images from NEU dataset :
| ![Sample images from NEU dataset](https://github.com/smahesh2694/NEU_XAI/blob/master/NEU_dataset%20image.jpeg?raw=true) |
|:--:| 
| *Sample images of all 6 classes* |
