# Robust RTSP Handling Pipeline (Single-Model)

Real-time RTSP/IP camera pipeline with auto-reconnect and async/threaded design. Focused on reliability and single-model inference.

## Features
- Auto-reconnect for unstable RTSP feeds
- Async/threaded processing
- YOLO-based detection
- Lightweight and scalable

## Tech Stack
- Python
- OpenCV
- YOLO (Ultralytics)
- PostgreSQL / MongoDB (optional)

## Use Case
Perfect for lightweight deployments and edge-based surveillance.

## Installation & Launch

1. Clone the repo:
   ```bash
   git clone https://github.com/Mazen-Ahmed12/Robust-RTSP-handling-auto-reconnect-async-threaded-pipeline.git
   cd Robust-RTSP-handling-auto-reconnect-async-threaded-pipeline

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. then run the app
   ```bash
   python app.py

## note 
  - dont forget to change the directories of the model and any other directory in the project
  - dont forget to run mongodb database before running the project
  - the models you can use whatever model you want even a custome one but dont forget the model extension
  - dont forget to change the RTSP_URL to the cam url 
