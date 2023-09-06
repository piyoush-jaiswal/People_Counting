# People Counting Project using Computer Vision and YOLOv7

## Overview

This repository contains the code and resources for a People Counting Project that uses Computer Vision and the YOLOv7 object detection model to count the number of people in a given area or video stream in real-time. The project is designed to provide accurate and efficient people counting for various applications, including crowd management, security, and retail analytics.

![People Counting Demo](people_count.gif.gif)

## Features

- Real-time people detection and counting.
- YOLOv7 object detection model for accurate person identification.
- Graphical user interface (GUI) for real-time visualization.
- Historical data logging and reporting.
- Alert and notification system for crowd threshold management.
- Easy deployment in various environments.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/piyoush-jaiswal/People-Counting.git
   cd People-Counting
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Download the YOLOv7 model weights from the official repository and place them in the `models/` directory. You can find the YOLOv7 model weights [here](https://github.com/WongKinYiu/yolov7).

## Usage

1. Launch the application:

   ```bash
   python main.py
   ```

2. Use the GUI to select the video feed or image source you want to analyze.

3. The application will start real-time people counting and display the results on the GUI.

4. Historical data and reports can be accessed and exported from the GUI.

5. Configure alert thresholds and notifications in the settings.

## Configuration

You can customize the project by modifying the configuration files in the `config/` directory. Here are some key configuration options:

- `config.yml`: General project settings.
- `thresholds.yml`: Define alert thresholds for crowd management.
- `cameras.yml`: Configure video sources and parameters.

## Acknowledgments

- YOLOv7: https://github.com/WongKinYiu/yolov7

## Questions or Issues

If you have any questions or encounter issues with the project, please open an issue on the [GitHub repository](https://github.com/piyoush-jaiswal/People-Counting/issues).

---

Feel free to expand and tailor this README to provide more specific information about your project, including detailed usage instructions, troubleshooting tips, and any additional features or customizations.
