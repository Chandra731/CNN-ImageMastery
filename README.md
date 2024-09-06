
# CNN Projects

## Overview
This repository contains three Convolutional Neural Network (CNN) projects, each focusing on different aspects of image classification:

1. **Fashion Industry Classification**  
2. **Black & White Image Classification**  
3. **Color Image Classification**

These projects are aimed at showcasing the power of CNNs in image recognition tasks. Each project involves training a CNN model on different datasets to classify images effectively.

---

## Project Structure

1. **Fashion Industry Classification**: Classify various clothing items using the Fashion MNIST dataset.
2. **Black & White Image Classification**: Apply CNNs to grayscale images to recognize objects.
3. **Color Image Classification**: Handle the complexity of color images with RGB channels for classification.

---

## 1. Fashion Industry Classification

### Project Highlights

* **Dataset:** Fashion MNIST: 28x28 grayscale images of 10 clothing categories.
* **Model Architecture:** Convolutional layers, MaxPooling, Dense layers, Dropout for regularization, ReLU activation, and Softmax for output probabilities. Adam optimizer for efficient training.
* **Evaluation:** Achieved an accuracy of **90%** on the test set.

### Instructions

1. Clone the repository.
2. Navigate to the `Fashion_Industry_Classification` directory.
3. Execute the Jupyter Notebook: `CNN_for_Fashion_Industry.ipynb`.

---

## 2. Black & White Image Classification

### Project Highlights

* **Dataset:** You can use either a custom dataset or a pre-defined one containing grayscale images.
* **Model Architecture:** Leverages CNNs for grayscale image feature extraction.
* **Flexibility:** Adaptable to various grayscale image classification scenarios.
* **Evaluation:** Achieved an impressive accuracy of **99%** on the test set.

### Instructions

1. Clone the repository.
2. Navigate to the `Black_&_White_image_Classification` directory.
3. Execute the Jupyter Notebook: `Black_&_White_image_classification.ipynb`.
4. **Important:** Prepare your grayscale image dataset or load a pre-defined one within the notebook.

---

## 3. Color Image Classification

### Project Highlights

* **Dataset:** Utilize either a custom dataset or a standard one comprising color images.
* **Model Architecture:** Designed to handle RGB color channels for intricate image classification tasks.
* **Evaluation:** Achieved an accuracy of **77%** on the test set.

### Instructions

1. Clone the repository.
2. Navigate to the `Color_Image_Classification` directory.
3. Execute the Jupyter Notebook: `CNN_Color_image_classification.ipynb`.
4. **Important:** Prepare your color image dataset or load a pre-defined one within the notebook.

**Installation:**
' pip install -r requirements.txt '

## Usage

* Each project has its corresponding Jupyter Notebook.
* Open and run the notebooks to train and evaluate the models.
* Explore the impact of model architecture and hyperparameter adjustments on performance.

## Results

* The Black & White Image Classification project achieved the highest accuracy (99%), followed by Fashion Industry Classification (90%).
* The Color Image Classification project had a slightly lower accuracy (77%), highlighting the increased complexity of classifying color images.

## License

MIT License - see the [LICENSE](LICENSE) file.

## Acknowledgments

- Thanks to [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist) for providing the dataset used in the first project.
- Special thanks to the open-source community for providing the tools and frameworks that made these projects possible.
