1. Extract all files from Zip File and make a note of the file path

2. You will find the coursework notebook and pickle files for basic and best models from the extracted folders
	1. Neural Network Notebook Humza Khan.ipynb   	#Notebook
	2. mlp_basic.sav
	2. mlpgrid.sav			#Best MLP model
	4. svm_basic.sav
	5. svmgrid.sav			#Best SVM model / Best performing model
	6. requirements.txt             #Installing relevant packages

-- For cases to create a virtual environment follow all the steps in points 3 and 4 below and install relevant packages -- 

3. Open anaconda command prompt, change directory (cd\) to the extracted folder
e.g.  C:\Users\HumzaKhan\Extracted_Folder

4. Create new virtualenv and install packages from the requirements.txt file;

a) Install Virtual Environment	
conda create -n virtualenv python=3.8

b) Proceed (y) to activate virutalenv

c) Install packages
pip install -r requirements.txt

d) Install a Jupyter Kernal
ipython kernel install --user --name=.venv

e) Run Jupyter notebook
jupyter notebook
	

-- Instructions for loading the best trained MLP and SVM models --
To load the pickle files open the Notebook and the code can be found under best MLP and SVM headings 'Random Search'.
1. mlpgrid.sav To load the best trained mlp model (Cell 121)
2. svmgrid.sav To load the best trained svm model (Cell 138)


