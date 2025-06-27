# 💫 Skin Type Classification Using Convolutional Neural Networks (CNN)

## Project summary
This project aimed to develop a model that can automatically classify face skin types (normal and oily) from images, with potential applications in skincare and dermatology.
A total of 600 images were used in the experiment, divided into 480 for training, 60 for validation, and 60 for testing.
A pre-trained VGG16 model, based on Convolutional Neural Networks (CNNs), was fine-tuned for this binary classification task. 
CNNs form the core architecture of VGG16, enabling effective feature extraction from images.
The model achieved an **accuracy of 81.67%**, demonstrating good performance on the dataset.

| ![Image Testing](https://github.com/user-attachments/assets/2d5b492d-26c6-46dc-9ffd-e971893d4890) | ![Classification Results](https://github.com/user-attachments/assets/ae7a54d0-75b7-422e-ba46-8fd04b258ff6) |
|:--:|:--:|
| Image Testing | Classification Result |

## Outcome summary
<p align="center">
  <img src="https://github.com/user-attachments/assets/258b1208-0d82-4947-917d-c854c5addcab" width="400"/>
</p>

- Oily skin: Out of 28 test images, 24 were correctly classified, while 4 were misclassified as normal skin.
- Normal skin: Out of 32 test images, 25 were correctly identified, with 7 incorrectly predicted as oily skin.

Overall, the model shows promising performance with more correct predictions than incorrect ones.
However, the presence of some misclassifications indicates room for improvement, especially in reducing false positives and negatives.

## Recommendation
- Expand the dataset with more varied and higher-resolution skin images to improve model generalization.
- Add a “Dry” skin class to turn the model into a multi-class classifier for more comprehensive results.
- Apply data augmentation (e.g., brightness, zoom, rotation) to reduce overfitting and improve robustness.
- For better real-world performance, consider building a webcam-based real-time classification system with lightweight models like MobileNet.
  
## Technologies used
`Python` `TensorFlow` `Keras` `VGG16` `CNN` 
`scikit-learn` `pandas` `numpy` `matplotlib`
