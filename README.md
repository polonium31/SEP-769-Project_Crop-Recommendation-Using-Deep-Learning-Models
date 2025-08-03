# Crop Recommendation Using Deep Learning Models on Soil and Weather Parameters

## Project Overview

With rising food demand and increasingly unpredictable climate conditions, farmers need smarter tools to make optimal crop choices. This project leverages deep learning to recommend the **top 3 most suitable crops** for a given combination of **soil features** (e.g., nitrogen, phosphorus, potassium) and **environmental parameters** (e.g., temperature, humidity, pH, rainfall). By training models on a real-world dataset, we aim to support precision agriculture and enhance sustainable farming practices.

## Project Structure

- `dataset`/
  - `Crop_recommendation.csv` # Raw dataset from Kaggle
- `models`/
  - `best_model.h5` # Saved Keras model
- `notebooks`/
  - `Crop_Recommendation_Model.ipynb` # Jupyter notebook for full pipeline
  - `Crop_Recommendation_Model.py` # Python script version
- `README.md` # Project documentation

---

## Technologies Used

- **Python 3.7+**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – Preprocessing and benchmarking
- **TensorFlow/Keras** – Deep learning implementation
- **Google Colab** – Development environment

## How to Run

### Prerequisites

- Python 3.7+
- Git
- pip

### Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/polonium31̀`/SEP-769-Project_Crop-Recommendation-Using-Deep-Learning-Models
cd Crop-Recommendation-Using-Deep-Learning

# 2. Create and activate a virtual environment (optional)
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

# 3. Run the notebook or script
jupyter notebook notebooks/Crop_Recommendation_Model.ipynb
# OR
python Crop_Recommendation_Model.py
`
```

# Dataset Source

**Source:** Kaggle - Crop Recommendation Dataset

### Features:

- **N:** Nitrogen content in soil
- **P:** Phosphorus content
- **K:** Potassium content
- Temperature
- Humidity
- pH
- Rainfall

**Label:** Crop to be grown (multi-class)

## Team Members and Contributions

### Jainish Patel

- **Contributions:** Model Development, Training, Deployment
- **GitHub Profile Link:** [Jainish Patel](https://github.com/polonium31)

### Mayur Patel

- **Contributions:** Data Analysis, Documentation, Evaluation
- **GitHub Profile Link:** [Mayur Patel](https://github.com/mayur045)

---

# Project Details

- **Course:** SEP 769:Cyber Physical Systems
- **Institution:** McMaster University, W Booth School of Engineering Practice and Technology
- **Term:** Summer 2025
- **Objective:** Deliver a reliable and scalable crop recommendation engine based on environmental inputs using deep learning.
