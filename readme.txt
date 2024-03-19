# Coursework Repository

This repository contains coursework materials for a machine learning project. Below is a guide to help you navigate through the files and set up the environment for running the provided code

## Contents

1. **Notebooks:**
   - `Neural Network Notebook Humza Khan.ipynb`: Coursework notebook containing machine learning models
   
2. **Pickle Files:**
   - `mlp_basic.sav`: Pickle file for the basic MLP model
   - `mlpgrid.sav`: Pickle file for the best performing MLP model
   - `svm_basic.sav`: Pickle file for the basic SVM model
   - `svmgrid.sav`: Pickle file for the best performing SVM model
   
3. **Other Files:**
   - `requirements.txt`: List of required Python packages

## Setup Instructions

If you wish to recreate the environment and run the code, follow these steps:

1. **Extract Files:** Extract all files from the provided zip file and make a note of the file path

2. **Navigate to Directory:**
   - Open Anaconda Command Prompt
   - Change directory (`cd`) to the extracted folder. For example:
     ```
     cd C:\Users\HumzaKhan\Extracted_Folder
     ```

3. **Create Virtual Environment:**
   a) Install Virtual Environment:
      ```
      conda create -n virtualenv python=3.8
      ```
   b) Activate Virtual Environment:
      ```
      conda activate virtualenv
      ```
      
4. **Install Packages:**
   - Install required packages listed in `requirements.txt`:
     ```
     pip install -r requirements.txt
     ```
     
5. **Install Jupyter Kernel:**
   - Install a Jupyter kernel for the virtual environment:
     ```
     ipython kernel install --user --name=.venv
     ```

6. **Run Jupyter Notebook:**
   - Start Jupyter notebook:
     ```
     jupyter notebook
     ```

## Loading Trained Models

To load the trained MLP and SVM models, follow these instructions:

1. **Open Notebook:**
   - Open the notebook `Neural Network Notebook Humza Khan.ipynb`

2. **Navigate to Model Loading Section:**
   - Look for the section labeled 'Random Search' under both MLP and SVM headings

3. **Load Models:**
   - For MLP model: Execute Cell 121 to load `mlpgrid.sav`
   - For SVM model: Execute Cell 138 to load `svmgrid.sav`

## Note

Make sure you have the necessary dependencies installed and the Jupyter notebook is configured with the virtual environment kernel before running the provided code
