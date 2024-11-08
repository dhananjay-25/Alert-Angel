# Vultr-Cloud-Hackathon
# Project: Alert Angel


## Project Description

**Alert Angel** is a real-time, AI-powered surveillance system designed to enhance public safety by automatically detecting distress or violent actions from video feeds. Using the pretrained I3D model from TensorFlow Hub, the system processes video frames to detect specific actions that indicate possible emergency situations, such as running, crouching, or falling. Once an actionable event is detected, an alert can be generated to notify the appropriate authorities or security personnel.

## Repository Structure

```plaintext
├── Data Preprocessing/
│   ├── data-preparation.ipynb       # Notebook for data preprocessing
│   ├── download_videos.ipynb        # Notebook for downloading video segments
|── dataset/                     # Folder containing processed dataset
│   ├── filtered_train_data.csv  # Filtered training data
│   └── filtered_val_data.csv    # Filtered validation data
├── Model Implementation/
│   └── implementation.ipynb         # Notebook for model implementation and inference
├── .gitignore                       # Git ignore file
├── LICENSE                          # Project license
└── README.md                        # Project documentation

```

“Requirements ------------ * 
**Python**: 3.7 or higher * 
**Dependencies**: See `requirements.txt` 
Getting Started --------------- 
1. **Clone the Repository**: `git clone https://github.com/username/AlertAngel.git cd AlertAngel`
2. **Install Dependencies**: `pip install -r requirements.txt`
3. **Run Action Detection**: The following command initiates the detection which processes video segments and uses the pretrained I3D model for predictions.


