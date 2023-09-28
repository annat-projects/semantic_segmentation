# Semantic Segmentation for Self Driving Cars

A semantic segmentation model that enables vehicles to understand and interpret their surroundings (cars, roads, obstacles etc.).

This model is trained using a dataset of road scenes from the CARLA self-driving car simulator. 
The dataset includes images with corresponding pixel-level annotations that specify the semantic class of each pixel.

Key components of the project include:

## Model Architecture:
Implemented a U-Net architecture with encoder and decoder blocks, skip connections, custom layers and metrics tailored for semantic segmentation.

## Optimizations:
Optimizations are performed to enhance model performance, including the use of custom callbacks for monitoring and saving the best models during training.
EarlyStopping callback monitors validation loss and stops training if it doesn't improve for 5 consecutive epochs.

## Training:
Training the model using TensorFlow/Keras.

## Evaluation:
Assessing the model's performance using metrics such as Dice coefficient, IoU, and cross-entropy loss.

## Inference:
Models' performance is evaluated on the test dataset:
- loss: 0.0984
- accuracy: 0.9702
- IoU: 0.7234
- DiceMetric: 0.7982

![image](https://github.com/annat-projects/semantic_segmentation/assets/19928756/d6dbdf48-568f-4ae7-9d49-034e67026b79)

![image](https://github.com/annat-projects/semantic_segmentation/assets/19928756/94c86794-341d-46e0-bd0a-4817ef08db2f)

![image](https://github.com/annat-projects/semantic_segmentation/assets/19928756/ce90ef71-56cf-492e-87b4-e074c0f9dd8e)

![image](https://github.com/annat-projects/semantic_segmentation/assets/19928756/79603fa4-7ed2-4fd3-8e7d-92669f9d76f3)
