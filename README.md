# Bat Speed Analysis

This repository contains a project that analyzes bat speed using computer vision techniques. The project is designed to detect and track a bat in a video, calculate its speed, and output a video with the results annotated.

## Project Workflow

The process for analyzing the bat speed involves the following steps:

1. **Problem Understanding**: Understanding the requirements for detecting bat speed in a video.
   
2. **Data Collection and Preprocessing**: Loading the video and preparing the data for analysis.

3. **Object Detection and Tracking**: Using a pre-trained YOLOv5 model to detect and track the bat in the video frames.

4. **Background Removal**: Optional step to remove the background for clearer analysis.

5. **Calculating Bat Speed**: Calculating the speed of the bat based on its movement between frames.

6. **Output Video**: Creating an output video with the bat speed annotated.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- tqdm (for progress bar)
- YOLOv5 weights and configuration files

## Installation

 Clone the repository:
    ```bash
    git clone https://github.com/yourusername/bat-speed-analysis.git
    ```


## Usage

1. Place your input video in the project directory and name it `input_video.avi`.
2. Ensure that the YOLOv5 weight files (`yolov5.weights` and `yolov5.cfg`) and the class names file (`coco.names`) are in the project directory.
3. Run the Jupyter notebook or execute the script to start the analysis:
    ```bash
    jupyter notebook Crick\ Analysis.ipynb
    ```
4. The output video with the detected bat speed will be saved as `output_combined.avi`.

## Results

The output video will show the detected bat along with the calculated speed at each frame where the bat is detected.

## Contributing

Feel free to open issues or pull requests if you have suggestions for improving the project.
