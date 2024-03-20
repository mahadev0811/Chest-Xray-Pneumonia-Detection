# Pneumonia Detection with Convolutional Neural Networks (CNN)

- This repository contains code to build, train, and evaluate a Convolutional Neural Network (CNN) model for pneumonia detection from chest X-ray images. 
- With just a few lines of code, you can create a powerful deep learning model to assist in diagnosing pneumonia. 
- This repo is designed for beginners who are starting to learn PyTorch or CNN.

## Introduction

- Pneumonia is a common and potentially life-threatening condition that affects millions of people worldwide. Rapid and accurate diagnosis is crucial for effective treatment. 
- This project aims to demonstrate how deep learning techniques, specifically CNNs implemented using PyTorch, can aid in the detection of pneumonia from medical images.

## Notebook Contents

1. **Data Loading**: Utilize PyTorch's DataLoader to efficiently load and preprocess the chest X-ray images dataset.
2. **Model Architecture**: Define a CNN architecture tailored for pneumonia detection, leveraging PyTorch's neural network modules.
3. **Training**: Train the CNN model on the dataset to learn the features indicative of pneumonia presence.
4. **Inference**: Evaluate the trained model's performance on unseen data and infer pneumonia presence from new chest X-ray images.

## Dataset

- The dataset used in this project consists of chest X-ray images collected from public repositories, containing both normal and pneumonia-affected images. 
- You can find the dataset on Kaggle: [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia).

## Usage

To run the notebook and reproduce the results:

1. Clone this repository:
    
    ```bash
    git clone https://github.com/mahadev0811/Chest-Xray-Pneumonia-Detection.git
    ```

2. Install torch and torchvision, visit [PyTorch](https://pytorch.org/get-started/locally/) for installation instructions, only after installing torch and torchvision, run the following command:

    ```bash
    pip install -r requirements.txt
    ```

3. Open the notebook in Jupyter Notebook or Google Colab and run the cells.

## Results

- After training the CNN model, you can expect to achieve an accuracy of over 90% on the test set on around 10 epochs of training. 
- The model's performance may vary based on hyperparameters, dataset size, and other factors.

## Contributions

Contributions to this project are welcome! If you have any ideas for improvements, bug fixes, or feature additions, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to [Paul Mooney](https://www.kaggle.com/paultimothymooney) for providing the dataset used in this project.