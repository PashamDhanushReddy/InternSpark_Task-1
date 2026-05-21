# ML Classification Project (Task 1)

**GitHub Repository:** [https://github.com/PashamDhanushReddy/InternSpark_Task-1.git](https://github.com/PashamDhanushReddy/InternSpark_Task-1.git)

This project builds and evaluates a supervised classification model to predict whether a breast tumor is malignant or benign using the Breast Cancer Wisconsin dataset.

## Environment Setup

To run the notebook locally, you need to set up a Python virtual environment and install the dependencies.

### Windows (PowerShell)

1. Open PowerShell in this directory (`task1`).
2. Run the setup script to create a virtual environment and install required libraries:
   ```powershell
   .\setup.ps1
   ```
   *(This creates a `venv` folder and installs pandas, scikit-learn, matplotlib, seaborn, and nbformat).*

3. Activate the virtual environment manually:
   ```powershell
   .\venv\Scripts\Activate.ps1
   ```

## How to View and Run

**1. Jupyter Notebook:**
Open the `breast_cancer_classification.ipynb` file in VSCode (with the Jupyter extension installed) or manually run `pip install jupyter` in the virtual environment to launch Jupyter Notebook.

**2. Document & Report:**
- `Task1_ML_Classification.docx` contains a high-level overview, links to the code, and all evaluation metrics/screenshots (ROC Curve and Confusion Matrices).
- `classification_report.md` serves as a quick text summary of the results.

## Deliverables Included
- **Notebook**: `breast_cancer_classification.ipynb` 
- **Summary Report**: `classification_report.md` 
- **Word Document**: `Task1_ML_Classification.docx` 
