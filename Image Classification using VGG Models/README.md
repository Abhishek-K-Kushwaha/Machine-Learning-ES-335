# Binary Classification Comparison of Different Models

This folder contains the implementation and comparison of various models for a binary classification task. The tasks performed include:

## Dataset Creation

### Objective:
To create a balanced dataset with two classes for training and testing various models on a binary classification task.

### Process:
1. **Data Collection**:
   - Used resources to download 100 images for each class, resulting in a total of 200 images.
   - Resources included automated bulk image download scripts and manual downloading.
   - The dataset can be accessed [here](https://drive.google.com/drive/folders/1vDNwJbFHmKc5HonQi0tyOEYPocTDRgSP?usp=sharing).
     
2. **Data Splitting**:
   - Split the dataset into 80 images per class for training and 20 images per class for testing.
   - Ensured a balanced representation of both classes in training and testing sets.

## Model Implementation and Training

### Models:
1. **VGG (1 block)**:
   - Implemented a shallow VGG-like model with one convolutional block.
2. **VGG (3 blocks)**:
   - Implemented a deeper VGG-like model with three convolutional blocks.
3. **VGG (3 blocks) with Data Augmentation**:
   - Applied data augmentation techniques to the VGG (3 blocks) model to improve generalization.
4. **Transfer Learning with VGG16/VGG19 (All Layers Tuned)**:
   - Utilized pre-trained VGG16 or VGG19 models and fine-tuned all layers.
5. **Transfer Learning with VGG16/VGG19 (Only Final Layers Tuned)**:
   - Utilized pre-trained VGG16 or VGG19 models and fine-tuned only the final fully connected layers.

### Training:
- Trained each model on the training dataset.
- Monitored training time, training loss, and training accuracy.
- Evaluated models on the test dataset to obtain testing accuracy.

## Tensorboard Visualization

### Objective:
To visualize the training and testing processes using Tensorboard.

### Process:
1. **Logging Scalars**:
   - Recorded and visualized training loss versus iterations.
   - Recorded and visualized training accuracy versus iterations.
   - Recorded and visualized testing accuracy versus iterations.

2. **Logging Images**:
   - Displayed all images from the test set along with their predicted labels.

### Purpose:
To provide a clear and interactive way to monitor and understand model performance during training and evaluation.

## Insights

### Objective:
To analyze and discuss the performance and behavior of different models based on the experiments.

### Topics Covered:
1. **Results Analysis**:
   - Discussed whether the results were as expected and possible reasons for any deviations.
2. **Impact of Data Augmentation**:
   - Evaluated the effectiveness of data augmentation in improving model performance.
3. **Fine-Tuning Epochs**:
   - Investigated the significance of the number of epochs used for fine-tuning the models.
4. **Model Confusion**:
   - Identified any specific images or patterns that caused confusion for the models and discussed possible reasons.

## MLP Model Comparison

### Objective:
To compare the performance of an MLP model with the VGG-based models.

### Process:
1. **MLP Implementation**:
   - Designed an MLP model with a comparable number of parameters to VGG16.
   - Choose an appropriate distribution of neurons and layers to match the complexity of VGG16.

2. **Training and Evaluation**:
   - Trained the MLP model on the same training dataset.
   - Compared the performance metrics, such as training time, training loss, training accuracy, and testing accuracy, with those of the VGG models.

### Conclusion:
- Provided detailed conclusions based on the comparison between the MLP and VGG models, highlighting the strengths and weaknesses of each approach.

