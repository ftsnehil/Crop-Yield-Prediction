# 🌾 Crop Yield Prediction using Machine Learning

Crop Yield Prediction is a Machine Learning web application built with **Flask** that predicts crop yield using agricultural and environmental parameters. The project aims to assist farmers, researchers, and agricultural planners in making informed decisions through data-driven predictions.

---

## 📖 Overview

Crop Yield Prediction is a regression-based Machine Learning project that estimates crop yield using historical agricultural data. The application takes various environmental and farming-related inputs, preprocesses the data, and uses a trained **Decision Tree Regressor** model to generate accurate predictions.

The project demonstrates the complete machine learning pipeline, including data preprocessing, model training, model serialization, and deployment using Flask.

---

## ✨ Features

- Predict crop yield using Machine Learning.
- Interactive web interface built with Flask.
- Real-time crop yield prediction.
- Data preprocessing before prediction.
- Lightweight and user-friendly application.
- Fast prediction using a trained model.

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Machine Learning
- Scikit-learn
- Pandas
- NumPy

### Backend
- Flask

### Frontend
- HTML
- CSS
- Bootstrap

### Development Tools
- Git
- GitHub
- VS Code

---

## 🤖 Machine Learning Model

- **Algorithm:** Decision Tree Regressor
- **Problem Type:** Regression
- **Framework:** Scikit-learn

---

## 📊 Dataset Information

The model is trained on historical agricultural data containing the following features:

| Feature | Description |
|---------|-------------|
| Year | Year of cultivation |
| Average Rainfall | Rainfall (mm/year) |
| Pesticides Used | Pesticides used (tonnes) |
| Average Temperature | Temperature (°C) |
| Area | Agricultural region |
| Crop Item | Crop name |

### 🎯 Target Variable

- Crop Yield (hg/ha)

---

## 📂 Project Structure

```text
Crop-Yield-Prediction/
│
├── app.py
├── CropYield-Prediction.ipynb
├── dtr.pkl
├── preprocessor.pkl
├── yield_df.csv
├── requirements.txt
├── README.md
└── templates/
    └── index.html
```

---

## ⚙️ Workflow

1. Collect agricultural data.
2. Clean and preprocess the dataset.
3. Train the Decision Tree Regression model.
4. Save the trained model and preprocessing pipeline.
5. Deploy the model using Flask.
6. Accept user inputs through the web interface.
7. Predict crop yield.
8. Display the predicted result.

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/ftsnehil/Crop-Yield-Prediction.git
```

### Navigate to the Project Directory

```bash
cd Crop-Yield-Prediction
```

### Create a Virtual Environment

```bash
python -m venv .venv
```

### Activate the Virtual Environment

**Windows**

```bash
.venv\Scripts\activate
```

**Linux/macOS**

```bash
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## 💻 Usage

1. Enter the required agricultural details.
2. Provide information such as rainfall, temperature, pesticides used, crop type, and area.
3. Submit the form.
4. The trained Machine Learning model predicts the expected crop yield instantly.

---

## 🎯 Applications

- Smart Agriculture
- Precision Farming
- Crop Yield Estimation
- Agricultural Research
- Farm Planning
- Decision Support Systems

---

## 🔮 Future Enhancements

- 🌦️ Weather API Integration
- 📊 Interactive Analytics Dashboard
- 🤖 Support for Multiple Machine Learning Models
- ☁️ Cloud Deployment
- 📱 Mobile-Friendly User Interface
- 📈 Improved Prediction Accuracy

---

## 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push to your branch.
5. Open a Pull Request.

---

## 👨‍💻 Author

**Snehil Kumar Amber**

GitHub: https://github.com/ftsnehil

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgements

This project was developed to demonstrate the practical application of Machine Learning in agriculture. It showcases data preprocessing, model training, and Flask-based deployment to build a real-world crop yield prediction system.

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub!
