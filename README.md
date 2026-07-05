# 🩺 Pneumocare - Pneumonia Detection Web Application
Welcome to Pneumocare. We empower healthcare professionals with high-precision, AI-driven chest X-ray analysis. By integrating advanced deep learning into the diagnostic workflow, Pneumocare enhances accuracy and accelerates the detection of pneumonia when every minute counts.

---
## 👤 My Contribution (Team Project)

- Built the **Flask backend** (`app.py`), including routing, image upload handling, and integration of the trained CNN model into the web application.
- Connected the preprocessing and inference pipeline to the web interface, enabling real-time prediction display for uploaded chest X-ray images.

Model training and dataset preparation were handled by teammates.

---
## 🌟 Features :
| Feature                | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| 📷 **X-ray Analysis**  | Upload chest X-ray images for pneumonia detection.                         |
| 📊 **Model Accuracy**  | Built with a robust deep learning model for high accuracy.                 |
| 🌐 **Web Interface**   | User-friendly interface for easy navigation and image uploads.             |
| 📁 **Multiple Formats**| Supports `.jpg`, `.png`, and `.jpeg` image formats.                        |
| ⚡ **Fast Processing**  | Get results in seconds with our optimized model.                          |
---
## 🛠️ How It Works :
1. **Upload**: Navigate to the "Upload" section and upload a chest X-ray image. 📤
2. **Processing**: The image is analyzed by our deep learning model. 🧠
3. **Results**: The application displays whether pneumonia is detected or not. ✅❌
---
## 📋 Image Requirements :
| Requirement            | Details                                                                   |
|------------------------|---------------------------------------------------------------------------|
| 📂 **File Format**     | `.jpg`, `.png`, `.jpeg`                                                   |
| 📏 **Resolution**      | Minimum resolution of **512 x 512 pixels**                                |
| 📦 **File Size**       | Maximum file size of **5MB**                                              |
---
## 🧠 About the Model :
- **Architecture**: Convolutional Neural Network (CNN) with multiple layers for feature extraction.
- **Input Shape**: `(200, 200, 3)` for resized X-ray images.
- **Training Data**: Trained on a dataset of labeled chest X-ray images.
- **Performance**: Achieves high accuracy on test data.
---
## 🚀 Getting Started :
1. Clone the repository:
```bash
   git clone https://github.com/your-repo/pneumonia-detection.git
2. Navigate to the project directory:
    cd pneumonia-detection
3. Install dependencies:
    pip install -r requirements.txt
4. Run the application:
    python app.py
5. Open your browser and navigate to:
    http://localhost:5000.
---
## 📂 Project Structure :
| File/Folder             | Description                                                              |
|-------------------------|--------------------------------------------------------------------------|
| `templates/`            | Contains HTML templates for the web interface.                          |
| `static/`               | Contains CSS and other static files.                                    |
| `detection_model.ipynb` | Jupyter Notebook for training the pneumonia detection model.             |
| `app.py`                | Flask application for serving the web interface.                        |
| `README.md`             | Documentation for the project.                                          |
---
## 🛡️ Disclaimer :
This application is for educational purposes only and should not be used as a substitute for professional medical advice. Always consult a healthcare professional for medical concerns.
---
## ❤️ Contributing :
We welcome contributions! Feel free to submit issues or pull requests to improve the project. 🙌
---
## 🌟 Thank You!
Thank you for using **Pneumocare**! Together, let's make healthcare smarter and more accessible. 🌍✨
```
