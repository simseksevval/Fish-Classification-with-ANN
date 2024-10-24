# Fish Classification with ANN
* The goal of this project is to develop a classification model using Artificial Neural Networks (ANN) to accurately identify and categorize various species of fish based on their images. With a dataset comprising 9 different fish species, each containing 1000 PNG images, this project aims to leverage the capabilities of neural networks in image recognition.
  
* The notebook contains:
  - Import Libraries
  - Import Dataset
  - Exploratory Data Analysis and Data Preprocessing
    - Extracting Image Paths and Labels
    - Dataset Recognition
    - Visualization of the Number of Observations
    - Displaying Dataset Images
    - Pixel Value Distribution
    - Image Resizing and Normalization
    - One-Hot Encoding
  - Train/Test Split
  - Creating the Model
  - Training the Model

* About Model:
  - **Input Layer**: Flattens the input images.
  - **Hidden Layers**: Four dense layers with 512, 256, 128, and 64 neurons, respectively, using ReLU activation.
  - **Output Layer**: Uses softmax activation to classify into `num_classes`.

The model is compiled with the Adam optimizer and categorical cross-entropy loss, suitable for multi-class classification. This architecture provides a foundation for various image classification projects.
