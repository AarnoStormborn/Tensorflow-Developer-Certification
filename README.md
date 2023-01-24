# Tensorflow Developer Certification

In this repository, I keep track of my course work in Zero to Mastery: Tensorflow Developer Certification on Udemy.
### Content

* **Notebook 0**: Introduction to Tensorflow
    - Matrix and Tensors
    - Tensor operations
    - Tensor Functions
    - **Dataset**: None
* **Notebook 1**: Regression with Tensorflow
    - Basic Regression models
    - Regression Problems and Metrics
    - Data Splitting and Evaluation
    - Scikit Learn Preprocessing and `ColumnTransformer`
    - **Dataset**: Medical Insurance Charges
* **Notebook 2**: Classification with Tensorflow
    - Classifcation problems and their types (binary, multiclass, multilabel)
    - Activation Functions
    - Finding Best Learning rate - `LearningRateScheduler` Callback
    - Classification Metrics and Confusion Matrix
    - **Dataset**: Fashion MNIST
* **Notebook 3**: Computer Vision with Tensorflow
    - Downloading and inspecting image data
    - End-to-End Example, Loading and Preprocessing images with `ImageDataGenerator`
    - Baseline Convolutional Nueral Network and speeding up training with GPU
    - Image Binary Classification
    - Dealing with Overfitting
        - Add MaxPooling layers
        - Add more data
        - Add regularization layers (`Dropout` `BatchNormalization`)
        - Add Data Augmentation
    - Data Augmentation
    - Image Multiclass Classification
    - Saving and Loading Models
    - **Dataset**: 
        1. Food101_Pizza_Steak
        2. Food101_10_classes 
* **Notebook 4**: Transfer Learning with Tensorflow - Feature Extraction
    - Load and Inspect data
    - Explore Tensorflow hub for pretrained models
    - Setup callbacks - Tensorboard for experiment tracking
    - Transfer Learning Models
        - ResNet50V2
        - EfficientNetB0
    - Compare Model experiments with Tensorboard.dev
    - **Dataset**:
        1. 10% Food101_10_classes
* **Notebook 5**: Transfer Learning with Tensorflow - Fine Tuning
    - Creating Helper Functions and import script
    - Tensorflow Functional API
    - Getting a Feature Vector from Transfer Learning model
    - Pooling with `GlobalAveragePooling2D` layer
    - Load images with `images_dataset_from_directory`
    - Series of Model Experiments: EfficientNetB0
        1. Model 0 : Feature Extraction with 10% data
        2. Model 1 : Feature Extraction with 1% data with augmentation
        3. Model 2 : Feature Extraction with 10% data with augmentation
        4. Model 3 : Fine Tuning with 10% data with augmentation
        5. Model 4 : Fine Tuning with 100% data with augmentation
    - Data Augmentation as a Sequential Layer
    - Model Checkpoint callback to save model/model weights during training
    - Compare Model results with Tensorboard.dev
    - **Dataset**:
        1. 1% Food101_10_classes
        2. 10% Food101_10_classes
        3. 100% Food101_10_classes
