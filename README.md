# YOLOv8 and SAM Integration for Real-Time Pothole Detection and Segmentation

## Description
This project demonstrates how to use a custom-trained YOLOv8 model for detecting potholes and integrate it with the Segment Anything Model (SAM) for precise, zero-shot segmentation of potholes. It also computes and displays the area of each pothole segment in real-time video footage captured from a car dashcam. 

### Project Workflow:
1. Custom training of YOLOv8 for pothole detection.
2. Real-time pothole detection on dashcam video.
3. Integration of YOLOv8 with Meta's Segment Anything Model (SAM) for segmentation.
4. Real-time area calculation and annotation of pothole areas.


### Prerequisites
- Python 3.8+
- YOLOv8 (Ultralytics)
- Segment Anything Model (SAM) from Meta AI
-

### Steps to Run
1. **Install Dependencies**
   ```bash
   pip install ultralytics segment_anything opencv-python matplotlib  numpy
   ```

2. **YOLO and SAM Model Preparation**
   - Place your custom YOLO model (`best.pt`) and SAM model checkpoint (`sam_b.pt`) in the project folder.

3. **Running the Application**
   - Execute the provided Jupyter Notebook (`yolo-sam.ipynb`) or Python script to perform inference on video.



### License
This project is for educational purposes.

### Authors
- Your Name: Dr T.K.Senthil Kumar

---


