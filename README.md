# ASL Recognition Project

## Overview
This project focuses on **American Sign Language (ASL) recognition** using **Convolutional Neural Networks (CNNs)** for classification and **YOLO (You Only Look Once)** for object detection. The model processes hand gesture images to recognize ASL signs effectively.

## Features
- **Dataset Loading**: Prepares and processes ASL image datasets.
- **Feature & Label Indication**: Defines input features and target labels.
- **Data Splitting**: Divides data into training and testing sets.
- **CNN Model Creation**: Implements a CNN for ASL recognition.
- **Data Augmentation**: Enhances dataset diversity for better generalization.
- **YOLO for Object Detection**: Detects hands and gestures in real-time.

## Installation
To run this project, install the required dependencies:
```bash
pip install tensorflow keras opencv-python numpy matplotlib
```

## Usage
1. **Load Dataset**: Ensure the ASL dataset is available in the project directory.
2. **Train the Model**: Run the Jupyter Notebook to train the CNN model.
3. **Test the Model**: Evaluate the model's accuracy on the test dataset.
4. **Object Detection**: Utilize YOLO for real-time ASL recognition.

## Project Structure
```
ASL_Project/
├── dataset/           # ASL image dataset
├── models/            # Trained models
├── notebook.ipynb     # Jupyter Notebook with implementation
├── README.md          # Project documentation
└── requirements.txt   # Dependencies
```

## Future Enhancements
- Improve model accuracy with additional ASL signs.
- Implement real-time ASL translation using webcam input.
- Optimize YOLO detection for better performance.

## Contributors
- **Your Name** - Sara Elwakeel

## License
This project is open-source and available under the MIT License.

