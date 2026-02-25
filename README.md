# Insurance_Premium_Prediction

🏥 Insurance Premium Prediction

A Machine Learning powered Insurance Premium Category Prediction system built using Python, FastAPI, and Streamlit.
The application predicts whether a user's insurance premium category will be Low, Medium, or High, along with confidence score and class probabilities.

🚀 Tech Stack
   - Python
   - Jupyter Notebook (Model development & experimentation)
   - Machine Learning (Scikit-learn)
   - FastAPI (Backend API)
   - Streamlit (Frontend UI)
   - Pydantic (Data validation & schema management)
   - Pickle (Model serialization)


⚙️ Features
✅ Smart Feature Engineering (Backend)
Using Pydantic computed fields:
  - BMI Calculation
  - Lifestyle Risk Classification
  - Age Group Segmentation
  - City Tier Classification (Tier 1, 2, 3)

✅ Robust API Validation
  - Input validation using Pydantic
  - Strict schema-based responses
  - Health check endpoint
  - Versioned model deployment

✅ Model Output
  - Predicted Premium Category
  - Confidence Score
  - Probability Distribution across all classes


🧠 ML Model Details
The trained model:
  - Loaded from model.pkl
  - Uses engineered features:
    - bmi
    - age_group
    - lifestyle_risk
    - city_tier
    - income_lpa
    - occupation
  - Outputs:
    - predicted_category
    - confidence
    - class_probabilities
