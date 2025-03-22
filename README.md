#  Deepfake Detection

This repository contains a **Deepfake Detection System** that utilizes **deep learning** techniques to identify manipulated videos. With the rise of AI-generated content, it has become crucial to differentiate real from fake media. This project provides an intuitive **web-based interface** for users to upload videos and receive real-time predictions. 🧠🎥

## ✨ Features
✅ **Deepfake detection** using a trained **CNN model**.  
✅ **User-friendly web interface** for seamless interaction.  
✅ **Support for video uploads** and **frame-wise analysis**.  
✅ **Interactive visualization** of deepfake detection results.  
✅ **Scalable architecture** for real-time processing.  
✅ **High accuracy detection model** trained on **Celeb-DF-v2 dataset**.

## 📊 About the Dataset: Celeb-DF-v2
The **Celeb-DF-v2 dataset** is a **large-scale dataset** specifically designed for deepfake detection. It contains **thousands of real and fake videos** generated using advanced deepfake techniques, making it a reliable dataset for training deep learning models.  

## 🚀 Installation Guide

Follow these steps to set up the Deepfake Detection System on your local machine:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/AhamedHassian/Deepfake_detection.git
   cd Deepfake_detection
   ```

2. **Install the required dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

3. **Download the pre-trained model**:  
   📥 [Download Model](https://drive.google.com/uc?id=1A2B3C4D5E6F7G8H9I0J&export=download)  
   **Note:** After downloading, place the model file in the `models/` directory and by the way, the Uploaded_Files folder is empty by default, so Git won’t track it unless there’s something inside. Just make sure to create the folder manually or add a dummy file (like .gitkeep) to keep it in the repo!

4. **Run the application**:
   ```sh
   python app.py
   ```

## 🛠️ Usage Instructions
1. Open the **web interface** in your browser.  
2. **Upload a video** that you suspect might be a deepfake.  
3. The **model processes** the video and performs **frame-wise analysis**.  
4. View the **detection results** with confidence scores. 📊  


## 📂 Project Structure
```
Deepfake_detection/
│── model/                # 🧠 Pretrained models
│── static/               # 🎨 Static files (CSS, JS, etc.)
│── templates/            # 📄 HTML templates for the web UI
│── Uploaded_Files/       # 📂 Folder for uploaded videos (empty by default)
│── app.py                # 🎭 Main application script
│── requirements.txt      # 📜 Dependencies
```

## 🤝 Contributing
We welcome contributions! 🚀 If you have ideas, improvements, or bug fixes, feel free to submit **issues** or **pull requests**. Let’s make deepfake detection better together! 💡

## 📜 License
This project is licensed under the **MIT License**. 📄 Feel free to use and modify it!

## 👨‍💻 Authors
👤 **Ahamed Hassian J**  
🔗 LinkedIn: [Ahamed-Hassian](https://www.linkedin.com/in/Ahamed-Hassian)  
