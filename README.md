# Computer Vision: Finger Detection and Counting

## Project Overview
This project utilizes computer vision techniques to detect human hands and count the number of fingers displayed. The application is developed in Python using OpenCV, offering real-time finger counting capabilities.

### Features
- Real-time hand recognition and finger counting.
- Utilizes background subtraction for hand segmentation.
- Implements thresholding and contour detection for precise finger identification.

## Technical Details
- **Language**: Python
- **Libraries**: OpenCV, NumPy, Scikit-learn
- **Concepts**: Image Thresholding, Background Subtraction, Contour Detection, Convex Hull.

## Installation and Usage
Ensure you have Python installed along with the necessary libraries: OpenCV, NumPy, and Scikit-learn.

1. Clone the repository:
   ```bash
   git clone [your-repo-link](https://github.com/Shreyaar12/Finger_Detection_CV)
   ```
2. Navigate to the cloned directory and run the notebook Hand_detection.ipynb 

## How It Works
1. The application captures live video feed from the camera.
2. The region of interest (ROI) for hand detection is defined.
3. Background subtraction and thresholding are applied to segment the hand.
4. The segmented hand is then processed to count the fingers using convex hull and contour detection algorithms.

## Contributions
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.


---

