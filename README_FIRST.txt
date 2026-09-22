STUDENT DROPOUT EARLY WARNING SYSTEM

HOW TO SET UP ON A NEW WINDOWS LAPTOP

1. Install Python 3.12

2. Open PowerShell in this folder

3. Create environment:

py -3.12 -m venv .venv

4. Activate:

.\.venv\Scripts\Activate.ps1

5. Install dependencies:

python -m pip install --upgrade pip
pip install -r requirements.txt

6. Run tests:

python -m pytest -q

7. Run website:

python -m streamlit run app.py

8. Open:

http://localhost:8501


IMPORTANT FILES

app.py
- Main Streamlit application

models\uci_sem1\dropout_early_warning_model.joblib
- Final trained Random Forest model

data\student_dropout.csv
- Original final modeling dataset

data\sample_batch_students.csv
- Demo batch upload

src\
- Final model training / feature code

tests\
- Project tests


BASIC EDITING WORKFLOW

Edit
→ Run localhost
→ Test
→ Commit
→ Push


DO NOT casually replace or edit the .joblib model file.
