# 💡 Propounding First Artificial Intelligence Approach

This is a **minor project** developed using **Python**, **Django**, and **Deep Learning**, aimed at predicting robbery behavior in indoor security camera environments. It uses **low-resolution surveillance data** and applies intelligent pattern recognition techniques to assist in early detection and crime prevention.

---

## 🚀 Project Overview

The system leverages a **Convolutional Neural Network (CNN)** and **fuzzy inference methods** to detect and classify suspicious robbery behaviors such as:
- Mugging (Class 0)
- Purse Snatching (Class 1)

Using structured input fields like event timestamps, neighborhood location, and camera metadata, the model outputs behavioral risk predictions in real-time.

---

## 🔧 Key Modules

- `Remote_User/` – UI for users to upload data and receive predictions
- `Service_Provider/` – Admin panel for managing datasets and training
- `templates/` – HTML pages + UI assets
- `Datasets.xlsx` – Training/test data with labels and metadata
- `Results.xlsx` – AI prediction output

## 📁 Folder Structure
propounding_first_artificial_intelligence_approach/
├── Remote_User/
├── Service_Provider/
├── Template/
│ ├── *.html
│ └── images/
├── Datasets.xlsx
├── Results.xlsx
├── manage.py

## 🛠️ Tech Stack

- **Backend**: Python, Django
- **AI/ML**: CNN, Fuzzy Inference
- **Libraries**: NumPy, Pandas, scikit-learn, Matplotlib
- **Frontend**: HTML, CSS
- **Platform**: Localhost Web App
  
## 📊 Dataset

- `Datasets.xlsx` – contains input data used in the project
- `Results.xlsx` – stores output or model evaluation results
- ## 📊 Dataset Fields (from Datasets.xlsx)

- `Fid`, `event_unique_id`, `occurrencedate`, `location_type`
- `Neighbourhood`, `Longitude`, `Latitude`
- `Prediction` → Output class (0 or 1)
