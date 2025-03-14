# ImagoAI_ML_INTERN_Task

1. Overview
This project predicts DON (Deoxynivalenol) concentration in grain samples using various machine learning models, including XGBoost, tuned XGBoost, and Transformers. The Transformer model provided the best results, outperforming traditional ML approaches.
2. Installation Instructions
2.1 Clone the Repository
bash
Copy
Edit
git clone <repository_url>
cd <repository_folder>
2.2 Create a Virtual Environment (Optional but Recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
2.3 Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Running the Code
3.1 Run the Preprocessing and Model Training Script
bash
Copy
Edit
python train.py
3.2 Evaluate the Model
bash
Copy
Edit
python evaluate.py
