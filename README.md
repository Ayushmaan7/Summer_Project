# Summer Project

## Overview
This project is a comprehensive application that combines various functionalities, including video downloading, image processing, communication tools, and cloud services. It leverages several libraries to provide a rich user interface and powerful capabilities.

## Features
1. **Video Downloader**: Download YouTube playlists and videos.
2. **Photo Capture**: Capture images using the webcam.
3. **Image Processing**: Crop photos, perform face swapping, and create custom images.
4. **Video Capture**: Capture live video from the webcam.
5. **Geolocation**: Get geographical coordinates for a specified city.
6. **Google Search**: Fetch the top 10 search results for a given query.
7. **Instagram Bot**: Automate posting images to Instagram.
8. **AWS Integration**: Launch EC2 instances, create S3 buckets, and send messages using SNS.
9. **Messaging**: Send WhatsApp messages and SMS using Twilio.
10. **Pomodoro Timer**: A simple Pomodoro timer for productivity.
11. **Game**: Play Rock, Paper, Scissors using hand gestures.

## Requirements
- Python 3.x
- Required Libraries:
  - Tkinter
  - OpenCV
  - PyWhatKit
  - Twilio
  - Boto3
  - Pillow
  - Geopy
  - Pytube
  - Pyttsx3
  - Pygame
  - NLTK
  - other libraries used in functions

## Installation
1. Clone this repository or download the code.
2. Install the required libraries using pip:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the main script:
   ```bash
   python main.py
   ```
2. Use the GUI to interact with different functionalities. Each button corresponds to a feature of the application.

## Function Descriptions
- `videoDownload()`: Downloads videos from YouTube playlists.
- `click_photo()`: Captures and displays a photo using the webcam.
- `crop_pic()`: Captures a photo and displays a cropped version.
- `face_swap()`: Swaps faces between two images.
- `capture_video()`: Captures live video from the webcam.
- `capture_crop_video()`: Captures video with a specific crop effect.
- `image_100_100()`: Creates and displays a simple custom image.
- `get_coordinates()`: Retrieves and prints geographical coordinates for a given city.
- `top_10_google_searches()`: Outputs the top search results for a specified query.
- `instabot()`: Automates posting an image to Instagram.
- `launch_instance()`: Launches a new EC2 instance on AWS.
- `create_bucket()`: Creates a new S3 bucket on AWS.
- `use_sns_service()`: Sends a message using AWS SNS.
- `whatsapp()`: Sends a WhatsApp message using PyWhatKit.
- `pomodoro()`: Implements a Pomodoro timer.
- `rock_paper_sci()`: Plays a game of Rock, Paper, Scissors using hand gestures.


