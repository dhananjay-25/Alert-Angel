# Vultr-Cloud-Hackathon
# Project: Alert Angel


## Project Description

**Alert Angel** is a real-time, AI-powered surveillance system designed to enhance public safety by automatically detecting distress or violent actions from video feeds. Using the pretrained I3D model from TensorFlow Hub, the system processes video frames to detect specific actions that indicate possible emergency situations, such as running, crouching, or falling. Once an actionable event is detected, an alert can be generated to notify the appropriate authorities or security personnel.

## Repository Structure

```plaintext
├── model implementation/
│   ├── action_detection.py        # Script for running action detection using pretrained I3D
├── data_processing/
│   ├── video_preprocessing.py     # Utility functions for downloading and processing video segments
├── config/
│   ├── config.yaml                # Configuration for model parameters and video input paths
├── main.py                        # Entry point to run the full pipeline
├── README.md                      # Project documentation
└── requirements.txt               # Python dependencies for easy setup
