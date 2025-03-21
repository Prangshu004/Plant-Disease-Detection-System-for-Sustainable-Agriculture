# 🌿 Plant Disease Detection System for Sustainable Agriculture

## 📌 Project Overview
This project leverages **AI/ML techniques** to identify plant diseases from leaf images, aiming to support sustainable agriculture by providing early disease detection. By using **image processing and deep learning models**, farmers can diagnose plant health issues and take preventive measures efficiently.

## 🚀 Features
- 🌱 **AI-powered Disease Detection** – Uses Convolutional Neural Networks (CNN) for accurate classification.
- 📸 **Image Processing** – Analyzes leaf images to detect symptoms of plant diseases.
- 📊 **User-Friendly Interface** – Simple and interactive UI for easy usage.
- 🛠 **Scalable & Efficient** – Designed for real-time analysis with minimal latency.

## 🏗 Tech Stack
- **Programming Languages**: Python
- **Libraries & Frameworks**: TensorFlow/Keras, OpenCV, NumPy, Pandas, Matplotlib
- **Machine Learning Model**: CNN (Convolutional Neural Networks)
- **Deployment**: Flask (for web app), Streamlit (optional UI), Docker (if applicable)

## 📂 Project Structure
```plaintext
📦 Plant-Disease-Detection
├── 📁 dataset/                  # Leaf images dataset
├── 📁 models/                   # Trained AI/ML models
├── 📁 notebooks/                # Jupyter Notebooks for model training & analysis
├── 📁 app/                      # Web application source code
│   ├── app.py                   # Main Flask/Streamlit app
│   ├── static/                   # CSS, JS files
│   ├── templates/                # HTML templates
├── requirements.txt             # Dependencies
└── README.md                    # Project documentation
```

## ⚙️ Installation & Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/prangshu004/plant-disease-detection-system-for-sustainable-agriculture.git
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**:
   ```bash
   python app.py
   ```
   Or for Streamlit UI:
   ```bash
   streamlit run app.py
   ```

## 📊 Model Training
If you want to train the model from scratch:
```bash
python train.py
```
Ensure you have the dataset placed inside the `dataset/` directory.

## 💡 Future Improvements
- 🔍 Enhance model accuracy with more diverse datasets.
- 🌎 Deploy the app using **AWS/GCP/Heroku**.
- 📲 Develop a **mobile-friendly version**.

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repository, raise issues, or submit pull requests.


🚀 **Made with ❤️ by [Prangshu]**
