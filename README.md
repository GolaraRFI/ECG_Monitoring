# ECG Monitoring with OpenCV

![ECG](https://github.com/GolaraRFI/ECG_Monitoring/assets/80590542/9862d4de-5ee0-4800-a01f-fac741a6cc96)

## Overview
This project is a simple code implementation for monitoring ECG (Electrocardiogram) using Python and OpenCV. The main objectives of this project are as follows:

1. Capture a video using the phone's camera.
2. Process the video frame by frame using the OpenCV library.
3. Calculate the mean value of all the pixels in each frame.
4. Plot the ECG signal in real-time.

## Project Structure
- `Vital_Sign.ipynb`: This Jupyter Notebook file contains the code for loading an ECG signal from a video file (`red_video.mp4`), extracting the red channel from each frame, and computing the instantaneous heart rate.

## Usage
1. Ensure you have the necessary Python libraries, including OpenCV, installed in your environment.
2. Open the `Vital_Sign.ipynb` notebook and run the cells to execute the code.
3. The code will process the video, calculate the ECG signal, and display the results.

Feel free to modify and customize the code to suit your specific requirements.

