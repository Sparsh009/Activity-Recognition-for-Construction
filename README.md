# Activity-Recognition-for-Construction
This project implements activity recognition for construction sites using deep learning models, including YOLOv9 for object detection and CNN-LSTM for activity recognition. The goal is to classify different types of construction-related activities and ensure safety compliance on-site through real-time video analytics.


## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [License](#license)
- [Authors](#authors)
- [Acknowledgments](#acknowledgments)

## Features
- Real-time object detection with YOLOv9.
- Activity recognition using a CNN-LSTM model.
- Classification of multiple construction activities to ensure compliance with safety standards.
- User-friendly interface for real-time monitoring.

## Technologies Used
- Python 3.8+
- PyTorch 1.7+
- OpenCV
- CUDA 11.0+ for GPU acceleration

## Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.8 or higher
- Pip package manager

### Setup
Clone the repository to your local machine:
```bash
git clone https://github.com/Sparsh009/Activity-Recognition-for-Construction.git
Navigate to the project directory:

bash
Copy code
cd Activity-Recognition-for-Construction
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Usage

To start the activity recognition system, run the following command in the terminal:

bash
Copy code
python main.py
Configuration
Edit the config.json file to adjust parameters such as model paths, input video paths, and output settings as needed.

Documentation

Further documentation detailing the architecture, models used, and customization options can be found in the docs folder.

Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
License

Distributed under the MIT License. See LICENSE for more information.

Authors

Sparsh - Initial work - Sparsh009
Acknowledgments

Thanks to everyone whose libraries were used in this project.
Special thanks to contributors and testers who have helped refine this system.
