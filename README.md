# Ocean Pollution Detection

## Overview

**Ocean Pollution Detection** is a deep learning-based project aimed at detecting and classifying marine debris from satellite imagery. By leveraging the MARIDA dataset and Sentinel-2 satellite images, this repository provides scalable tools for real-time environmental monitoring and effective pollution management.

## Features

- **Dataset**: Uses the MARIDA dataset combined with Sentinel-2 satellite imagery to identify and classify marine debris.
- **Multiple Algorithms**: Explores Random Forest, Stochastic Gradient Descent (SGD), and Convolutional Neural Networks (CNN).
- **Best-in-class Model**: The CNN model achieves the highest accuracy and precision for marine debris detection.
- **Real-Time Application**: Designed for deployment in real-time ocean monitoring systems.

## Technologies

- **Deep Learning**: Convolutional Neural Networks (CNN) for image classification.
- **Machine Learning**: Includes Random Forest and SGD for performance comparison.
- **Satellite Imagery**: Utilizes Sentinel-2 satellite data.
- **Dataset**: MARIDA dataset for training and validation.

## Results

- The CNN model significantly outperforms other machine learning techniques in both accuracy and precision.
- Demonstrates the capability of deep learning to support real-time environmental monitoring and pollution management.

## Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/parthkadiya772/Ocean_Pollution_Detection.git
    cd Ocean_Pollution_Detection
    ```

2. **Requirements**
    - python == 3.7.10
    - pytorch == 1.7 
    - cudatoolkit == 11.0 (For GPU usage, compute capability >= 3.5)
    - gdal == 2.3.3
    - rasterio == 1.0.21
    - scikit-learn == 0.24.2
    - numpy == 1.20.2
    - tensorboard == 1.15
    - torchvision == 0.8.0
    - scikit-image == 0.18.1
    - pandas == 1.2.4
    - pytables == 3.6.1
    - tqdm == 4.59.0
    
    
    ### Installation Guide
    
    The requirements are easily installed via
    [Anaconda](https://www.anaconda.com/distribution/#download-section) (recommended):
    ```bash
    conda env create -f environment.yml
    ```
    > If the following error occurred: InvalidVersionSpecError: Invalid version spec: =2.7 
    >
    > Run: conda update conda
    
    After the installation is completed, activate the environment:
    ```bash
    conda activate marida
    ```

3. **Download the MARIDA dataset and Sentinel-2 imagery**
    - In order to train or test the models, download [MARIDA](https://doi.org/10.5281/zenodo.5151941)
    - Ensure you have access to the dataset and place it in the appropriate directory as specified in the code (For data stucture and follow the project check main project for [Marine Dabris](https://github.com/marine-debris/marine-debris.github.io)).

## Usage

1. **Train the model**
    - Run the training script (replace with actual script name if available):
        ```bash
        python train_cnn.py
        ```
    - You can also experiment with other algorithms like Random Forest or SGD by running their respective scripts.

2. **Evaluate the model**
    - Use the evaluation script to assess performance on test data:
        ```bash
        python evaluate.py
        ```

3. **Real-time detection**
    - Integrate the trained CNN model into your monitoring pipeline for real-time marine debris detection.

## Contributing

Contributions, issues, and feature requests are welcome! Please open an issue or submit a pull request for improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE.txt](LICENSE.txt) file for details.

## Security

See [SECURITY.md](SECURITY.md) for supported versions and how to report vulnerabilities.

## Acknowledgements

- MARIDA dataset
- Sentinel-2 satellite data

---

*For more details and documentation, please refer to the individual scripts and code comments.*
