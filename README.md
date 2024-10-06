# ShopLifters Detection Project

## A computer vision project aimed at detecting shoplifting behaviors from video data. This repository contains code for processing video frames and metadata, with plans to integrate a behavior classification model.

### Table of Contents

	1.	Overview
	2.	Features
	3.	Dataset
	4.	Installation
	5.	Usage
	6.	How It Works
	7.	Future Work
	8.	Contributing

### Overview

The ShopLifters Detection Project is designed to analyze surveillance video footage to identify potential shoplifting incidents. Using frame-by-frame analysis and video metadata, the project aims to build an automated shoplifting detection system leveraging machine learning.

Features

	•	Video Processing: Frame-by-frame extraction from videos for data analysis.
	•	Metadata Collection: Extracts video properties such as resolution, frame count, and video duration.
	•	Behavior Classification: A planned feature to detect shoplifting behavior using machine learning models.

### Dataset

The project uses a dataset consisting of multiple .mp4 video files, with varying frame counts and resolutions. Here are the key attributes of the videos:

	•	Resolution: 704x576 pixels.
	•	Frame Count: Ranges from 175 to 475 frames per video.
	•	File Format: Videos are stored in .mp4.

Sample metadata from the dataset:

{
  "file": "shop_lifter_n_0.mp4",
  "frames": 450,
  "width": 704,
  "height": 576
}

### Installation

To get started with the project, follow these steps:

	1.	Clone the repository:

git clone www.github.com/MSoffar/ShopLifters--MobileNet-LSTM

	2.	Navigate to the project directory:

cd ShopLifters--MobileNet-LSTM


	3.	Install the required dependencies

### Usage

Once the dependencies are installed, you can run the video analysis script:

python main.py

This script will process the videos, extract metadata, and prepare the data for further analysis or model training.

### How It Works

	•	Frame Extraction: The videos are processed to extract individual frames for analysis.
	•	Metadata Handling: Information such as frame count, resolution, and video duration are extracted from each video.
	•	Machine Learning: (Work in progress) A model will be trained to identify shoplifting behaviors based on frame data and other features.

### Future Work

	•	Computer Vision Model: Develop and integrate a model for automatic shoplifting detection.
	•	Performance Optimization: Improve the efficiency of video processing, particularly for larger datasets.
	•	Dataset Expansion: Use a larger and more diverse dataset to improve the model’s accuracy.

### Contributing

Contributions are welcome! If you’d like to contribute to the project, please follow these steps:

	1.	Fork the repository.
	2.	Create a new branch for your feature or bugfix.
	3.	Commit your changes and push to your branch.
	4.	Submit a pull request with a detailed explanation of your changes.
