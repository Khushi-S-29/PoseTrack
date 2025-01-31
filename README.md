# **Poseify: Human Pose Estimation App with OpenCV**

Poseify is a cutting-edge application designed to perform human pose estimation using OpenCV and TensorFlow models. With an intuitive interface powered by Streamlit, users can upload images and visualize skeletal key points and connections for pose analysis.

---

## 🚀 **Features**
- **Custom Image Upload:** Analyze poses by uploading images.
- **Keypoint Visualization:** Detect and connect essential body points.
- **Threshold Control:** Adjustable detection sensitivity for precise results.
- **User-Friendly UI:** Seamless interaction with a clean interface.

---

## 🔧 **Tech Stack**
- **Programming Language:** Python
- **Libraries & Tools:**
  - OpenCV
  - Streamlit
  - TensorFlow DNN
  - NumPy
  - Pillow

---

## ⚙️ **Installation Instructions**

1. Clone this repository:
   ```bash
   git clone [<repository-url>](https://github.com/Khushi-S-29/PoseTrack)
   ```
2. Navigate to the project directory:
   ```bash
   cd Poseify
   ```
3. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/MacOS
   venv\Scripts\activate    # For Windows
   ```
4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Run the Streamlit app:
   ```bash
   streamlit run estimation_app.py
   ```

---

## 📸 **Usage**

1. Upload an image containing a clear human figure.
2. Adjust the threshold slider to fine-tune keypoint detection.
3. View the processed image with the estimated pose.



Happy Coding! 🚀
