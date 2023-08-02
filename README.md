# Project-Face-Mask-Detection
Face mask detection project uses TensorFlow, Keras, OpenCV-Python, NumPy, Imutils, SciPy, and Matplotlib. It automates identifying mask-wearing in images or video streams, enhancing safety compliance effectively.
**Project Face Mask Detection**

![Face Mask Detection](https://github.com/atharvabhairam/Project-Face-Mask-Detection/raw/main/images/demo.gif)
![image](https://github.com/atharvabhairam/Project-Face-Mask-Detection/assets/91341989/632ee2c2-f4e6-4590-a86a-7234411478c9)

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to the **Project Face Mask Detection** repository! This project is aimed at developing an AI-based system to detect whether a person is wearing a face mask or not. The goal is to contribute to public safety and encourage the practice of wearing face masks to combat the spread of contagious diseases.

The project is implemented using computer vision techniques and deep learning algorithms. It employs the power of Convolutional Neural Networks (CNNs) to accurately identify the presence or absence of a face mask in real-time images or video streams.

## Prerequisites

Before getting started with the installation and usage, ensure you have the following prerequisites:

- Python (version 3.x)
- TensorFlow (version 2.x)
- OpenCV (version 4.x)
- Numpy
- Matplotlib

You can install these dependencies using the `requirements.txt` file provided in this repository.

## Installation

To set up the project, follow these steps:

1. Clone this repository to your local machine using the following command:

   ```
   git clone https://github.com/atharvabhairam/Project-Face-Mask-Detection.git
   ```

2. Navigate to the project directory:

   ```
   cd Project-Face-Mask-Detection
   ```

3. Install the required dependencies using pip:

   ```
   pip install -r requirements.txt
   ```

## Usage

Once you have installed all the prerequisites, you can use the face mask detection system as follows:

1. Ensure that your camera is connected and accessible to the Python script.

2. Run the main script to start the face mask detection application:

   ```
   python face_mask_detection.py
   ```

3. The application will open a window displaying the live camera feed. The system will automatically identify faces and draw bounding boxes around them, indicating whether the person is wearing a mask or not. Green bounding boxes indicate that the person is wearing a mask, while red bounding boxes signify that the person is not wearing a mask.

4. To exit the application, press 'q' on your keyboard.

## Contributing

Contributions to this project are welcome and highly appreciated. If you want to contribute, please follow these steps:

1. Fork this repository.

2. Create a new branch with a descriptive name:

   ```
   git checkout -b my-new-feature
   ```

3. Make your modifications and commit them:

   ```
   git commit -m "Add a new feature"
   ```

4. Push the changes to your fork:

   ```
   git push origin my-new-feature
   ```

5. Create a pull request explaining your changes and their benefits.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

