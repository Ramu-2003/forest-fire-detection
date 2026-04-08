# 🔥 Forest Fire Detection Using YOLO Models

A deep learning-based forest fire detection system using YOLO (You Only Look Once) models with a Flask web interface for real-time fire detection from images.

## � Team Members

This project is developed as a final year project by Computer Science Engineering (AI) students from Narasaraopeta Engineering College.

### Team Leader
**T. Jai Prakash**
- GitHub: [@Jaiprakash14](https://github.com/Jaiprakash14)
- Email: jaiprakashtirupathi97355@gmail.com
- Role: Deep Learning Model Development & Training

### Team Member
**G. Rama Krishna Prasad**
- GitHub: [@Ramu-2003](https://github.com/Ramu-2003)
- Email: ramu4012y@gmail.com
- Role: Web Application Development & Integration

## 📋 Table of Contents
- [Team Members](#team-members)
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Deep Learning Model Training](#deep-learning-model-training)
- [Work Distribution](#work-distribution)
- [Technologies Used](#technologies-used)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## 🌟 Overview

This project implements a forest fire detection system using computer vision and deep learning techniques. The system can analyze images and detect the presence of fire with high accuracy, helping in early fire detection and prevention.

## ✨ Features

- 🔥 Real-time fire detection from uploaded images
- 🎯 Multiple YOLO model support
- 🌐 User-friendly web interface built with Flask
- 📊 Confidence score display for predictions
- 🖼️ Support for multiple image formats (PNG, JPG, JPEG)
- 📱 Responsive design for mobile and desktop

## 📁 Project Structure

```
forest-fire-detection/
│
├── forest_fire_detection/
│   ├── app.py                      # Flask application
│   ├── requirements.txt            # Python dependencies
│   │
│   ├── fire/                       # Sample fire images (30 images)
│   │   └── *.jpg
│   │
│   ├── not_fire/                   # Sample non-fire images (31 images)
│   │   └── *.jpg
│   │
│   ├── static/                     # CSS and JavaScript files
│   │   ├── fire_detection.css
│   │   └── fire_detection.js
│   │
│   ├── templates/                  # HTML templates
│   │   ├── index.html
│   │   └── fire_detection.html
│   │
│   └── uploads/                    # Uploaded images storage
│
├── Forest_Fire_Detection_Using_Computer_Vision (1).ipynb
│                                   # Jupyter notebook for model training
└── README.md                       # This file
```

## 🚀 Installation

### Prerequisites

- Python 3.7 or higher
- pip (Python package manager)
- Git

### Step 1: Clone the Repository

```bash
git clone https://github.com/Ramu-2003/forest-fire-detection.git
cd forest-fire-detection
```

### Step 2: Navigate to Project Directory

```bash
cd forest_fire_detection
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

## 💻 Usage

### Running the Application

1. Make sure you're in the `forest_fire_detection` directory:
   ```bash
   cd forest_fire_detection
   ```

2. Run the Flask application:
   ```bash
   python app.py
   ```

3. Open your web browser and navigate to:
   ```
   http://127.0.0.1:5000/
   ```

4. Upload an image and select a model to detect fire

### Using the Web Interface

1. Click on "Fire Detection" or navigate to the detection page
2. Choose a YOLO model from the dropdown (Model 1, Model 2, or Model 3)
3. Upload an image (PNG, JPG, or JPEG format)
4. Click "Detect Fire" to get the prediction
5. View the results with confidence score

## 🧠 Deep Learning Model Training

The deep learning model training code is available in Google Colab for easy access and GPU support.

### Access the Training Notebook

🔗 **Colab Link**: [Forest Fire Detection Model Training](https://colab.research.google.com/drive/1v72XZbcSkkaqrxuqpUR1cGDQTbG_JvcR?usp=sharing)

### Training Steps

1. Open the Colab notebook using the link above
2. Make a copy of the notebook to your Google Drive
3. Run all cells sequentially to:
   - Load and preprocess the dataset
   - Train the YOLO model
   - Evaluate model performance
   - Export the trained model

4. Download the trained model weights
5. Integrate the model with the Flask application

### Alternative: Local Training

You can also run the Jupyter notebook locally:

```bash
jupyter notebook "Forest_Fire_Detection_Using_Computer_Vision (1).ipynb"
```

**Note**: Local training requires:
- CUDA-compatible GPU (recommended)
- PyTorch with CUDA support
- Sufficient RAM (8GB+ recommended)

## 🛠️ Technologies Used

- **Backend**: Flask 2.3.3
- **Deep Learning**: YOLO (You Only Look Once)
- **Frontend**: HTML5, CSS3, JavaScript
- **Image Processing**: Werkzeug 2.3.7
- **Model Training**: Python, PyTorch, Google Colab

## 👨‍💻 Work Distribution

### T. Jai Prakash (Team Leader)
- Deep learning model architecture design
- YOLO model training and optimization
- Dataset collection and preprocessing
- Model evaluation and performance tuning
- Jupyter notebook development for model training
- Integration of trained models with the application

### G. Rama Krishna Prasad
- Flask web application development
- Frontend design and user interface implementation
- Backend API development for image upload and prediction
- Static file management (CSS, JavaScript)
- HTML template creation and responsive design
- Project deployment and GitHub repository management

## 📸 Screenshots

*Add screenshots of your application here*

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## � Acknowledgments

- Our sincere gratitude to Narasaraopeta Engineering College for providing the resources and support
- Thanks to our project guide and faculty members for their valuable guidance
- YOLO team for the excellent object detection framework
- Forest fire dataset contributors
- Flask and PyTorch communities for comprehensive documentation
- Google Colab for providing free GPU resources for model training

## 📧 Contact

For any queries or suggestions, please open an issue on GitHub.

---

⭐ If you find this project helpful, please give it a star!
