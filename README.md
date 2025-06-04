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

2. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3. **Download the MARIDA dataset and Sentinel-2 imagery**
    - Ensure you have access to the dataset and place it in the appropriate directory as specified in the code.

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

## Folder Structure

- `/data`: Contains splits and references for training, validation, and test datasets.
- `/scripts` or `/src`: Source code for model training, evaluation, and data processing.

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
