# Stroke Risk Prediction System using ML

## Overview
The **Stroke Prediction System** is a machine learning-based web application that predicts the risk of stroke based on user-provided health details. The system utilizes five machine-learning models to enhance accuracy and provides a user-friendly interface for input submission. 

This project aims to assist in early stroke detection by analyzing key health factors such as age, BMI, smoking status, and medical history.

## Features
- **Machine Learning Models**: Uses five models
    - **K-Nearest Neighbors (KNN)**
    - **Logistic Regression (LR)**
    - **Random Forest (RFT)**
    - **Decision Tree (DT)**
    - **Support Vector Machine (SVM)** to improve prediction accuracy.
- **Pre-trained Models**: Models are trained and saved as `.pkl` files for quick inference.
- **Dataset Integration**: The system is trained on stroke-related medical datasets.
- **User-Friendly Interface**: Users can enter their details and get a stroke risk assessment.
- **Performance Evaluation**: Compares multiple models to provide the most accurate results.

## Tech Stack
- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **Machine Learning**: Scikit-learn, Pandas, NumPy
- **Data Storage**: Kaggle Excel Dataset

## Dataset
The dataset used for training consists of the following features:
- **Gender**
- **Age**
- **Hypertension** (1 = Yes, 0 = No)
- **Heart Disease** (1 = Yes, 0 = No)
- **Ever Married** (1 = Yes, 0 = No)
- **Work Type**
- **Residence Type** (1 = Urban, 0 = Rural)
- **Average Glucose Level**
- **BMI**
- **Smoking Status** (0 = Unknown, 1 = Formerly Smoked, 2 = Never Smoked, 3 = Smokes)

You can download the dataset from **Kaggle**:  
[Stroke Risk Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)


## Project Structure
```
Directory structure:
└── ganeshkantle-stroke-risk-prediction-using-ml/
    ├── README.md
    ├── requirements.txt
    ├── Files/
    │   ├── Project PPT.pptx
    │   └── Project Report.docx
    ├── Snapshots/
    └── Stroke Risk Prediction using ML/
        ├── Readme.md
        ├── Stroke Prediction using 5 ML Algorthms.ipynb
        ├── app.py
        ├── logistic.pkl
        ├── logistic.sav
        ├── dataset/
        │   └── healthcare-dataset-stroke-data.csv
        ├── models/
        │   ├── dt.sav
        │   └── scaler.pkl
        └── templates/
            ├── home.html
            ├── nostroke.html
            └── stroke.html
```

## Usage
1. **Enter the required details** (Gender, Age, Hypertension, Heart Disease, etc.).
2. **Click Submit** to get the stroke risk prediction.
3. **Get the result**, indicating whether there is a risk of stroke based on the provided data.

## Model Performance
| Model | Accuracy |
|--------|-----------|
| Logistic Regression (LR) | 94.61% |
| K-Nearest Neighbors (KNN) | 94.6% |
| Random Forest (RFT) | 94.22% |
| Decision Tree (DT) | 90.99% |
| Support Vector Machine (SVM) | 94.71% |

## Example Output
```
Input:
Gender: Male
Age: 45
Hypertension: 1
Heart Disease: 0
Ever Married: 1
Work Type: Private
Residence Type: Urban
Average Glucose Level: 150
BMI: 28.5
Smoking Status: 2

Output:
"High Risk of Stroke"
```

## Screenshots
### Attributes Used
![Attributes](https://github.com/user-attachments/assets/19d6685a-64d1-4fef-b959-570cd559a4e9)
### Home Page
![Home Page](https://github.com/user-attachments/assets/22369f71-ce4f-4c10-a7ef-5c2a7f960b9d)
### Input Box
![Input Box](https://github.com/user-attachments/assets/bcf499f5-9580-4638-855d-87714832d6a4)
### No Risk
![No Risk](https://github.com/user-attachments/assets/7752bfcd-f307-46bf-a7a5-d2546bbcf38b)
### Risk
![Risk](https://github.com/user-attachments/assets/3bfbdd1b-4dd7-4c92-a555-db28fd108961)



## Installation
### 1. Clone the Repository
```bash
git clone https://github.com/ganeshkantle/Stroke-Risk-Prediction-using-ML.git
cd Stroke-Risk-Prediction-using-ML 
```

### 2. Install Dependencies
Make sure you have Python installed, then run:
```bash
pip install -r requirements.txt
```

### 3. Run the Application
```bash
python app.py
```

### 4. Access the Web Application
Once the server is running, open your browser and go to:
```
http://127.0.0.1:3000/
```


## Contributing
If you'd like to contribute, please fork the repository and submit a pull request. All contributions are welcome!


## Contact
For any queries, feel free to reach out:
- **Email:** ganeshkantle@gmail.com
- **GitHub:** (https://github.com/ganeshkantle)
- **My Bento:** (https://bento.me/kantle)
- **My Portfolio:** (https://tinyurl.com/ganeshkantle)
