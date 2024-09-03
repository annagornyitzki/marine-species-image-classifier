# Marine Species Image Classifier with ML on GCP Using Jupyter Notebooks

## Table of Contents

- [Project Description](#projectdescription)
- [Tools and Technologies](#tools-and-technologies)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Description
This project involves building a machine learning model that automatically identifies and classifies marine species from underwater images. The model is designed for users to easily classify images by marine species. The project leverages Google Cloud Platform (GCP) for data storage, model training, deployment, and analysis. Python, SQL, JavaScript, and Jupyter notebooks are used throughout to ensure reliable data handling, model development, and user interaction.

## Tools and Technologies
- **Google Cloud Platform:**
  Cloud Storage, AI Platform, Cloud SQL, BigQuery, Cloud Functions, App Engine
- **Python:**
  Data preprocessing, model development, API creation, and interaction with GCP services
- **SQL:**
  Database management, querying, and data analysis (**In Progress will be done by 9/10/24**)
- **JavaScript:**
  For frontend development and visualization  (**In Progress will be done by 9/10/24**)
- **Jupyter Notebooks:**
  Data exploration, model experimentation, and documentation
  
## Dataset
- **Source**: [Link to dataset or description of how the dataset was gathered]
- **Classes**: [Number of classes and description]
- **Preprocessing**: Describe any preprocessing steps such as resizing, normalization, augmentation, etc.

## Model Architecture
- **Framework**: [TensorFlow, Keras, PyTorch, etc.]
- **Model Type**: [e.g., Convolutional Neural Network, Transfer Learning using ResNet, etc.]
- **Layers**: [Brief description of the model layers]
- **Activation Functions**: [e.g., ReLU, Softmax]
- **Loss Function**: [e.g., Categorical Crossentropy]
- **Optimizer**: [e.g., Adam, SGD]

## Training
- **Environment**: [Details of the hardware or cloud environment used, e.g., GCP Vertex AI, local machine with GPU, etc.]
- **Training Data Split**: [Training/Validation split ratio]
- **Batch Size**: [Number of images per batch]
- **Epochs**: [Number of training epochs]
- **Augmentation**: [Any data augmentation techniques applied]
- **Learning Rate**: [Initial learning rate and any decay schedule]


## Evaluation
- **Test Data**: [Description of the test dataset]
- **Metrics**: [Accuracy, Precision, Recall, F1-Score, etc.]
- **Confusion Matrix**: [Optional: Include a confusion matrix image or explain how to generate it]
- **ROC Curve**: [Optional: Include a ROC curve or explain how to generate it]

## Installation
### Prerequisites
- [Python version]
- [List of necessary libraries, e.g., TensorFlow, Keras, NumPy, etc.]

### Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    ```
2. Navigate to the project directory:
    ```bash
    cd your-repo-name
    ```
3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```


## Usage
1. **Training the Model**:
    ```bash
    python train.py --epochs 50 --batch_size 32
    ```
2. **Testing the Model**:
    ```bash
    python test.py --model_path path_to_saved_model --test_data path_to_test_data
    ```
3. **Predicting New Images**:
    ```bash
    python predict.py --image_path path_to_image --model_path path_to_saved_model
    ```

## Results
- **Final Accuracy**: [Training and testing accuracy]
- **Loss**: [Final loss values]
- **Sample Predictions**: [Optional: Include images with predictions overlaid]
- **Model File**: [Link to the saved model file, if available]

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request if you would like to contribute.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
- Email: annagornyitzki@gmail.com
- University: annagornyitzki@ucsb.edu
- LinkedIn: https://www.linkedin.com/in/anna-gornyitzki-016669288/
