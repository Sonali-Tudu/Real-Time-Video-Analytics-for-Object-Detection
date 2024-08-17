# Real-Time-Video-Analytics-for-Object-Detection

## Project Overview
The "Real-Time Object Detection in Video Stream" project aims to detect and draw bounding boxes around objects in a live video feed using advanced pre-trained object detection models like YOLO (You Only Look Once). This project enables real-time object recognition, offering high accuracy and efficiency for dynamic environments.

## Tech Stack
- **Python**:  Programming language used for developing the project.
- **OpenCV**: For video stream processing and drawing bounding boxes.
- **YOLO (You Only Look Once)**: Pre-trained object detection model for real-time object detection.
- **TensorFlow/PyTorch**: Backend for loading and running the YOLO model.
- **NumPy**: For numerical operations and data manipulation.
- **Matplotlib**: For creating data visualizations (if needed).
- **Jupyter Notebook**: For interactive analysis and development.

## Features
- Real-time video stream capture and processing.
- Integration of YOLO for object detection.
- Drawing bounding boxes around detected objects in the video feed.
- Support for various object categories (e.g., people, vehicles, animals).
- Adjustable detection thresholds and performance tuning.


## Data Sources
- **Pre-trained YOLO Model**: Available from sources like the official YOLO repository or other model repositories.

## Installation
Clone the Repository:
```
git clone https://github.com/your-username/real-time-object-detection.git
```
Create a Virtual Environment:
```
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
Install Dependencies:
```
pip install -r requirements.txt
```

## Usage
1. **Prepare the Model**: Download the pre-trained YOLO model weights and configuration files, and place them in the appropriate directory.
2. **Run the Jupyter Notebook**: Start the Jupyter Notebook server by running the command jupyter notebook and then open the object_detection.ipynb notebook.
3. **Run the Detection Script**: Execute the cells in the notebook to initialize the video capture, load the model, and start detecting objects in the video stream.
4. **View Real-Time Detection**: The notebook will display the live video feed with bounding boxes around detected objects, updating in real-time.


## Results
The project successfully demonstrates real-time object detection in live video streams using the YOLO model. The system efficiently identifies and localizes objects, drawing bounding boxes with minimal latency, making it suitable for dynamic, real-time applications.

## Contributing
Contributions are welcome! If you have suggestions or improvements, please create a pull request or open an issue.
