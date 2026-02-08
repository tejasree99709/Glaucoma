# Glaucoma Risk Prediction using Machine Learning

**Project Overview**

The Glaucoma Risk Prediction application is a Machine Learning–based web tool designed to assess whether a patient is at risk of developing glaucoma using important clinical and diagnostic metrics. Glaucoma is a serious eye condition that can lead to irreversible vision loss if not detected early. This application helps support early screening by providing quick, data-driven predictions.
The system uses a trained classification model and an interactive interface built with Streamlit, allowing users to input patient metrics and receive instant risk predictions.

**Features**

* Interactive and responsive Streamlit web application
* Real-time glaucoma risk prediction
* Supports both clinical and demographic input parameters
* Structured preprocessing aligned with model training
* Efficient and lightweight classification model
* Clear prediction messages with medical guidance
* Beginner-friendly Machine Learning deployment project

**Machine Learning Workflow**

1. Data collection and preprocessing
2. Feature selection based on clinical relevance
3. Encoding categorical variables
4. Training the classification model
5. Saving the trained model using Joblib
6. Building the Streamlit interface
7. Generating real-time predictions

**Tech Stack**

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Joblib

**Project Structure**

```
Glaucoma-Risk-Prediction/
│
├── app.py                      # Streamlit application
├── glaucoma_clf_model.pkl      # Trained classification model
├── requirements.txt           # Project dependencies
└── README.md
```

**Installation & Setup**

**1. Clone the Repository**

```bash
git clone https://github.com/your-username/glaucoma-risk-prediction.git
cd glaucoma-risk-prediction
```

**2. Create a Virtual Environment (Recommended)**

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

**3. Install Dependencies**

```bash
pip install -r requirements.txt
```

If the requirements file is not available, install manually:

```bash
pip install streamlit pandas numpy scikit-learn joblib
```

**4. Run the Application**

```bash
streamlit run app.py
```

The application will automatically open in your default web browser.

**How to Use**

1. Enter patient metrics using the sidebar controls.
2. Adjust sliders for numerical values such as age, intraocular pressure, and corneal thickness.
3. Select the appropriate categorical options including gender, family history, cataract status, and angle closure status.
4. Click the Predict Glaucoma Risk button.
5. View the prediction result along with recommended guidance.

**Model Information**

Algorithm Used: Classification Model for Glaucoma Risk Detection
