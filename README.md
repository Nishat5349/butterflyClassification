---
license: apache-2.0
---
# Butterfly Classification Using Deep Learning

## **Introduction:**

Embarking on the enchanting exploration of "Butterfly Classification using Deep Learning," our project harnesses the prowess of the MobileNetV2 algorithm within the TensorFlow framework to create an intricate model. This neural network, trained on a diverse dataset of butterfly images, achieves an impressive 98% accuracy during training and maintains a robust 95% accuracy in testing. Beyond the model's success, we extend the project's accessibility by developing a Gradio-based machine learning app. This intuitive application allows users to effortlessly input butterfly images, receiving swift and accurate predictions regarding the species classification. In this convergence of technology and nature, our project not only showcases the capabilities of deep learning in image recognition but also opens avenues for broader applications in ecological research and education.

## **Dataset**

For this project, i collected dataset from "https://www.kaggle.com/datasets/gpiosenka/butterfly-images40-species". Which contains Train, Test.Validation data set for 100 butterfly or moth species. All images are 224 X 224 X 3 in jpg format.

## **Model Architecture**

I applied **MobilenetV2** to train my model. I employ the **Adam optimizer** with a conservative learning rate of 0.0001.
This is the model summary:

![modelDef](https://github.com/Nishat5349/butterflyClassification/assets/72455268/88152745-59b8-4611-9529-ee870f49c3da)


The following shows the model performance:

![modelResult](https://github.com/Nishat5349/butterflyClassification/assets/72455268/7c995d6b-114f-403c-b1c9-b423e9ad1239)

![trainingValidationAccuracy](https://github.com/Nishat5349/butterflyClassification/assets/72455268/62617d41-e21e-46a7-9cc8-e0ebe7073f3a)

### I have launched a Gradio-based ML app on this...check it out here "https://github.com/Nishat5349/ML-app-for-Classification"



