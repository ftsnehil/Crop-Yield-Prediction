# Crop Yield Prediction using Machine Learning

A Flask-based Machine Learning application that predicts crop yield using agricultural and environmental parameters. The project leverages a Decision Tree Regressor to estimate crop production and provides a simple web interface for users to obtain predictions instantly.

---

## Overview

Crop Yield Prediction is a Machine Learning project designed to estimate crop yield based on historical agricultural data. The application accepts various environmental and farming-related inputs, preprocesses the data, and uses a trained Decision Tree Regressor model to generate predictions.

The project demonstrates the complete machine learning workflow, including data preprocessing, model training, model serialization, and deployment using Flask.

---

## Features

- Predict crop yield using Machine Learning.
- Web interface built with Flask.
- Real-time prediction based on user input.
- Data preprocessing pipeline for accurate predictions.
- Clean and lightweight application.
- Easy to run and extend.

---

## Technologies Used

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

---

## Machine Learning Model

- **Algorithm:** Decision Tree Regressor
- **Problem Type:** Regression
- **Framework:** Scikit-learn

---

## Dataset

The model is trained using historical agricultural data containing the following features:

| Feature | Description |
|---------|-------------|
| Year | Year of cultivation |
| Average Rainfall | Rainfall in mm/year |
| Pesticides Used | Pesticide usage in tonnes |
| Average Temperature | Temperature in °C |
| Area | Agricultural region |
| Crop Item | Crop name |

**Target Variable**

- Crop Yield (hg/ha)

---

## Project Structure

```text
Crop-Yield-Prediction/
│
├── app.py
├── CropYield-Prediction.ipynb
├── dtr.pkl
├── preprocessor.pkl
├── yield_df.csv
├── README.md
├── requirements.txt
└── templates/
    └── index.html
```

---

## Workflow

1. Collect and prepare agricultural data.
2. Clean and preprocess the dataset.
3. Train a Decision Tree Regression model.
4. Save the trained model and preprocessing pipeline.
5. Build a Flask web application.
6. Accept user inputs through the web interface.
7. Predict crop yield using the trained model.
8. Display the prediction to the user.

---

## Installation

### Clone the repository

```bash
git clone https://github.com/ftsnehil/Crop-Yield-Prediction.git
```

### Navigate to the project directory

```bash
cd Crop-Yield-Prediction
```

### Create a virtual environment

```bash
python -m venv .venv
```

### Activate the virtual environment

**Windows**

```bash
.venv\Scripts\activate
```

**Linux/macOS**

```bash
source .venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## Applications

- Smart Agriculture
- Crop Yield Estimation
- Agricultural Planning
- Precision Farming
- Research and Educational Purposes

---

## Future Enhancements

- Improve prediction accuracy using ensemble learning techniques.
- Integrate real-time weather data through external APIs.
- Deploy the application on cloud platforms.
- Develop a responsive user interface.
- Add visualization dashboards for agricultural insights.

---

## Requirements

- Python 3.x
- Flask
- Pandas
- NumPy
- Scikit-learn

Install all required packages using:

```bash
pip install -r requirements.txt
```

---

## Repository

GitHub Repository:

https://github.com/ftsnehil/Crop-Yield-Prediction

---

## Author

**Snehil Kumar Amber**

GitHub: https://github.com/ftsnehil

---

## License

This project is released under the MIT License.

---

## Acknowledgements

This project was developed to explore the practical application of Machine Learning in agriculture. It demonstrates how predictive analytics can support data-driven decision-making in crop production.

