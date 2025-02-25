
# Kidney Disease Classification Using Deep Learning  
[![Image](https://github.com/user-attachments/assets/33fdf211-09c4-48b6-97c8-204668cdea8f)](https://github.com/user-attachments/assets/33fdf211-09c4-48b6-97c8-204668cdea8f)


## 🚀 Overview  
This deep learning-based project classifies **CT scan images** of kidneys into **Stone, Cyst, Tumor, or Normal** categories. It uses **TensorFlow** for model training and a **Flask** web app for user interaction. The model predicts the condition and suggests consulting a doctor.  
## 🏗️ Architecture  
This project follows a **monolithic architecture**, where all components (model, preprocessing, and UI) are integrated into a single system.  
##  📌 Technologies Used

- **Deep Learning**: TensorFlow, CNN  
- **Backend**: Flask, Flask-Cors  
- **Frontend**: HTML, CSS, JavaScript  
- **Data Processing**: Pandas, NumPy, OpenCV  
- **Version Control**: DVC, MLflow  
- **Deployment**: Flask Server  
## 🛠️ Setup & Installation 


1. **Clone the  repo:**
   ```sh
   git clone https://github.com/your-username/  Kidney_Disease_Classification_Using_Deep_Learning.git
   cd Kidney_Disease_Classification_Using_Deep_Learning
   ```
2. **Install dependencies:**
  ```sh
     pip install -r requirements.txt
  ```
3. **Download the pre-trained model using DVC:**
    ```sh
     dvc pull
    ```
    *If you haven't initialized DVC, first run:*
      ```sh
      dvc init
      dvc remote add origin <your-remote-storage-link>
      dvc pull
    ```
    
   
4. **Run the Flask server:**

   ```sh
      dvc init
      dvc remote add origin <your-remote-storage-link>
      dvc pull
   ```
5. **Open http://127.0.0.1:5000 in your browser.**
## 📽️ Working Demo:

[![Watch the video](https://img.youtube.com/vi/KTYQGtX5C88/0.jpg)](https://youtu.be/KTYQGtX5C88)
## 📢 Contributing
Want to improve this project? Fork it, create a branch, make changes, and submit a Pull Request
