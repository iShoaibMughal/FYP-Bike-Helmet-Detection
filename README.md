# Bike-Helmet-Detectionv2
This repository contains the Bike Helmet detection using YOLOv8 in streamlit. This web application does processing on end users images and videos to detect **bike rider**, **helmet** and ***no helmet** and render processed images and videos to user.

# Major python libraries used for the project
```
# Below is the list of the major packages needed for working in this project.

ultralytics==8.1.8 # For running inference using YOLOv8 model
streamlit==1.30.0 # Web application
pillow==10.2.0 # For managing images and videos
pytube==15.0.0 # For running inference on small youtube videos
```

# File Structure
```
Bike-Helmet-Detectionv2
├── app.py
├── assets
│   ├── BikesHelmets6.png
│   ├── video_1.mp4
│   ├── video_2.mp4
│   └── video_3.mp4
├── .git
├── .gitignore
├── helper.py
├── images
│   ├── BikesHelmets6_detected.jpg
│   └── BikesHelmets6.png
├── local_requirements.txt
├── major_packages.txt
├── packages.txt
├── README.md
├── requirements.txt
├── runs
│   └── detect
│       └── predict
│           └── BikesHelmets6.png
├── settings.py
├── videos
│   ├── video_1.mp4
│   ├── video_2.mp4
│   └── video_3.mp4
└── weights
    ├── best.pt
    ├── information.txt
    └── last.pt
```

# How to run this streamlit webapp project locally?
```
python3 -m venv .venv
source .venv/bin/activate
git clone https://github.com/Viddesh1/Bike-Helmet-Detectionv2.git
cd Bike-Helmet-Detectionv2/
pip install -r requirements.txt
streamlit run app.py
```

Note:- If this app is not working locally then please add opencv-python==4.9.0.80 below before opencv-python-headless==4.8.1.78 and opencv-contrib-python==4.8.1.78 in requirements.txt file :-

```
opencv-python==4.9.0.80
opencv-python-headless==4.8.1.78
opencv-contrib-python==4.8.1.78
```
# Deployment Pipeline
Continuous delivery is done by streamlit to host on Streamlit Cloud through this Github repository. 

# Hosted on Streamlit:- 
https://bike-helmet-detectionv2-dmehozp3lkef4wnssaepjf.streamlit.app/

# Also see
1) https://github.com/Viddesh1/Helmet_test_1
2) https://github.com/Viddesh1/Bike-Helmet-Detection
3) https://github.com/Viddesh1/Bike-Helmet-Detection-Docs