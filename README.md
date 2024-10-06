##ShopLifters Detection Project

#Overview

#This project focuses on analyzing video footage to identify shoplifting behavior. The dataset consists of several videos of both shoplifters and non-shoplifters. The objective is to process the videos frame by frame and develop a system that can classify and detect potential shoplifting incidents.

Features

	•	Frame-by-frame video analysis: Extracts frames from videos for detailed analysis.
	•	Video metadata handling: Includes data such as the number of frames, resolution, and file name.
	•	Shoplifting behavior detection: Aims to automate the identification of shoplifting through machine learning (currently in progress).

Dataset Information

The dataset contains videos with the following attributes:

	•	Resolution: 704x576 pixels.
	•	Frame count: Ranges between 175 and 475 frames per video.
	•	File format: Videos are in .mp4 format.

Sample video metadata:

{
  "file": "shop_lifter_n_0.mp4",
  "frames": 450,
  "width": 704,
  "height": 576
}

Installation and Usage

	1.	Clone the repository:

git clone <repo-link>


	2.	Install the required dependencies:

pip install -r requirements.txt


	3.	Run the main script for analysis:

python main.py



How It Works

	•	Frame Extraction: The videos are processed frame by frame.
	•	Metadata Extraction: Collects and stores essential metadata like resolution and frame count.
	•	Behavior Classification: A machine learning model will be implemented to detect shoplifting based on video data.

Future Work

	•	Build and integrate a machine learning model for shoplifting detection.
	•	Optimize frame processing performance.
	•	Expand dataset size to enhance model accuracy.

Feel free to make any changes or let me know if there’s anything else you’d like to add!
