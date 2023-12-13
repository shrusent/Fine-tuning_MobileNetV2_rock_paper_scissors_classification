# Fine-tuning MobileNetV2 for rock, paper and scissors classification

This project is a part of a Machine Learning course.

# Creating a custom dataset:

A dataset of rock, papaer, scissor images were created using phone camera. The dataset link to drive : https://drive.google.com/drive/folders/1lLqlna14ztVHFnd6FO7pKxI2nTQGldEQ?usp=sharing.
It has in total 312 images in total and 3 categories: rocks-108, paper-106 and scissors- 107

Fine tuned the last few layers of MobileNetV2 trained on the weights of ImageNet database, with my custom dataset for performing this classification(used 3 neurons in the Dense layer for three categories in the dataset).MobileNetV2 is used due to its efficiency, speed, and adaptability to resource-constrained environments. The model strikes a balance between accuracy and computational cost, making it ideal for real-time applications on devices like mobile phones or edge devices. Its versatility, stemming from being pretrained on ImageNet, allows for effective transfer learning, especially when dealing with limited task-specific data.

The validation accuracy is 100 percent by fine tuning MobileNet model. Training accuracy is continuously increasing and is 98.04 percent. The test accuracy is also high 98.46 percent for this dataset.
