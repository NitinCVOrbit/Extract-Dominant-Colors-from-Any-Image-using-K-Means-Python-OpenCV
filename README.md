# 🎨 Dominant Color Extraction using K-Means Clustering

This project demonstrates how to **extract and visualize dominant colors from images** using **K-Means clustering** in Python. It leverages basic **Computer Vision** and **Machine Learning** concepts to analyze pixel distributions and generate a clear color composition bar for each image.

---

## 🚀 Project Overview

Images are made up of millions of pixels, each represented by RGB values. In this project:

* Each pixel is treated as a data point
* K-Means clustering groups similar colors together
* Cluster centers represent **dominant colors**
* A histogram is used to calculate how much each color contributes to the image

The final output includes:

* Original image
* A horizontal bar showing dominant colors and their proportions

---

## 🧠 How It Works

1. Load image using OpenCV
2. Convert image from BGR to RGB
3. Reshape image into a 2D array of pixels (N × 3)
4. Apply **K-Means clustering** on pixel values
5. Extract cluster centers (dominant colors)
6. Create a normalized histogram of cluster labels
7. Visualize dominant colors using a color bar
   
---

## 🛠️ Technologies Used

* Python 🐍
* OpenCV (cv2)
* NumPy
* Scikit-learn (KMeans)
* Matplotlib

---

## 🎯 Example Output

* Identifies top **K dominant colors**
* Shows **percentage contribution** of each color
* Helps understand color composition visually

---

## 📌 Use Cases

* Image analysis & segmentation
* Color palette generation
* UI/UX & graphic design inspiration
* Machine learning & computer vision learning
* Data visualization projects

---

## 🔮 Future Improvements

* Automatically detect optimal number of clusters
* Save dominant colors as HEX codes
* Real-time dominant color detection using webcam
* Convert project into a Streamlit web app

