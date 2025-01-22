# plant-disease-prediction-cnn-deep-leanring-project
![Screenshot 2025-01-21 081657](https://github.com/user-attachments/assets/54565305-6cd5-4a40-8b8f-fc9cf4f8bbed)

This repository is about building an Image classifier CNN with Python on Plant Disease Prediction.

![class distribution plant](https://github.com/user-attachments/assets/8aba3c1f-711b-4fc5-8600-fd9b1ab0273d)

Kaggle Dataset Link: https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset

## Setup Steps

1. **Create a Virtual Environment**
   ```bash
   python -m venv env

2. **Activate the Virtual Environment**
   ```bash
   .\env\Scripts\activate

3. **Install Dependencies**
   ```bash
   pip install -r app/requirements.txt

4. **Run the Application**
   ```bash
   streamlit run app/main.py

### Note on Model File

The trained model is not included in the repository. Instead, a `Link.txt` file is available in the `app/trained_model/` directory. This file contains a Google Drive link to download the model. Follow these steps to set up the model:

1. Open the `Link.txt` file located in the `app/trained_model/` directory.
2. Use the Google Drive link provided in the file to download the model.
3. Place the downloaded model file into the `app/trained_model/` directory.

Once the model file is in place, the application will function as intended.


