
# AI-Powered Chest X-Ray Analysis: Normal or Abnormal?

This project utilizes AI to analyze chest X-ray images and classify them as "Normal" or "Abnormal" using deep learning models. It is built using Python, Flask, and several key libraries for image processing and model inference.

## Features
- Upload chest X-ray images for analysis
- AI-powered model to detect abnormalities
- Flask web app interface for easy interaction

## Libraries and Dependencies
The project uses the following Python libraries:
- `Flask`: A lightweight web framework to create the web interface.
- `OpenCV`: A powerful library for image processing.
- `Ultralytics YOLO`: A state-of-the-art object detection model for analyzing X-ray images.
- `supervision`: A library used for visualization and monitoring of object detection results.
- `pyresearch`: A library to integrate research tools and processes.

## Installation Instructions

To set up this project, follow the steps below:

### 1. Clone the repository
```bash
git clone https://github.com/your-username/AI-Powered-Chest-X-Ray-Analysis.git
cd AI-Powered-Chest-X-Ray-Analysis
```

### 2. Create and activate a virtual environment (optional but recommended)
For Windows:
```bash
python -m venv venv
.env\Scriptsctivate
```

For macOS/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install the required libraries
Run the following command to install all dependencies:
```bash
pip install -r requirements.txt
```

Alternatively, you can install the libraries individually using:
```bash
pip install flask opencv-python ultralytics supervision pyresearch
```

### 4. Run the Flask application
Once all the dependencies are installed, you can start the web app by running the following command:
```bash
python app.py
```

### 5. Access the web app
Open your web browser and go to `http://127.0.0.1:5000/` to interact with the Chest X-Ray analysis tool.

## How it works
1. Upload a chest X-ray image.
2. The image is passed through a YOLO-based model for object detection.
3. The model analyzes the image and classifies it as "Normal" or "Abnormal".
4. The result is displayed in the web interface.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

