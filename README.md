# Tumor Detection

## Introduction
This project aims to detect and classify MRI images of the brain for the diagnosis of different brain tumors. We implement a convolutional neural network for image classification using the PyTorch framework.

## Dataset
The dataset used in this project consists of MRI images categorized into four classes:
- Notumor

![Notumor](images/notumor.png)

- Glioma

![Glioma](images/glioma.png)

- Meningioma

![Meningioma](images/meningioma.png)

- Pituitary

![Pituitary](images/pituitary.png)

## Implementation
We utilize PyTorch for building and training the convolutional neural network. The network architecture is designed to effectively classify MRI images into their respective tumor categories.

## Getting Started
To get started with the project:
* Clone the repository:
   ```bash
   git clone https://github.com/SaliDeveloper/tumor_detection.git
   ```

## Results

* Dataset distribution:

<img src="images/train_distribution.png" width="318"> <img src="images/test_distribution.png" width="318">

* Plot loss and accuracy during trining:

<img src="images/plot_loss_and_accuracy.png" width="680">

* evaluation results of the trained model on the test dataset:

<img src="images/evaluation_results.png" width="200">

## Contributions
Contributions to the project are welcome. If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
