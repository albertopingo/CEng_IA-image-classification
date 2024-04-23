# Image Classification Project README

## Objective
This project involves building and training convolutional neural network (CNN) models for image classification tasks using a provided dataset. The primary goals include using various CNN architectures, experimenting with different optimizers, implementing data augmentation techniques, and exploring transfer learning methods. The project requires a comprehensive report detailing all steps taken and analysis of experimental results.

## Dataset
- The dataset consists of 6 folders: 5 `train#` folders (e.g., `train1`, `train2`, etc.) and 1 `test` folder.
- Each group will use 4 `train#` folders for training and the remaining `train#` folder for validation based on a specified calculation involving student numbers.
- All groups will use the same `test` folder for final model evaluation.
- The images are RGB (three channels) and are intended for classification tasks.

## Requirements
1. **Dataset Processing (5%)**:
   - Preprocess the dataset for training, validation, and testing.
   - Describe the dataset characteristics.

2. **S Models (35%)**:
   - Design at least one CNN model (Model S) from scratch.
   - Experiment with different optimizers for training Model S.
   - Train Model S with and without data augmentation.
   - Evaluate and analyze Model S performance using metrics like accuracy, precision, recall, and F1 score.

3. **T Models (30%)**:
   - Implement transfer learning with both feature extraction and fine-tuning using pre-trained models (Model T).
   - Try different optimizers for training Model T.
   - Train Model T with and without data augmentation.
   - Compare and analyze the performance of Model T with different strategies.

4. **Report (20%)**:
   - Write a detailed report using notebook markdown annotations.
   - Include all steps taken to build and train models.
   - Describe experiments conducted, results obtained, and metric analyses (confusion matrices, charts, etc.).
   - Provide in-depth analysis and insights derived from the experiments.

5. **Extras (10%)**:
   - Innovate beyond standard course contents.
   - Examples of extras include regularization methods, deployment of models in applications, or custom data augmentation operations.

## Assessment
- **Dataset Processing (5%)**: Ensure proper dataset handling and description.
- **S Models (35%)**: Design, train, and evaluate custom CNN models.
- **T Models (30%)**: Implement and assess transfer learning methods.
- **Report (20%)**: Produce a comprehensive report detailing methodologies and findings.
- **Extras (10%)**: Bonus points for innovative approaches and additional functionalities.
