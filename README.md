**SVM Tutorial - The Impact of Hard and Soft Margins in SVMs**

This repository contains the dataset, codes, presentation, and video transcripts used in the tutorial titled **The Impact of Hard and Soft Margins in SVMs: 
How the Soft Margin Parameter C Influences Classification Performance**

**Projects**
This repository contains two .ipynb files.
1. SVM_HardMargin_SoftMargin.ipynb
2. Classification_OnlineRetailData.ipynb

**Projects Overview**
**1.SVM_HardMargin_SoftMargin.ipynb**
This file demonstrates
 - How SVM(Support Vector Machine) works: Hyperplane, margins, Support vectors
 - Hard Margin SVM: Explanation and visualization
 - Soft Margin SVM: Explanation and visualization
 - The effect of Cthe  parameter (Tested decision boundary for different C values)
   
**2. Classification_OnlineRetailData.ipynb**
  - Classify customers as frequent or infrequent using the UCI online retail dataset.
  - Data Preprocessing steps
      - Handling missing values and inconsistent data types
      - Data scaling using min-max scaler
      - SMOTE to address class imbalance
    - Hyperparameter tuning
      - Used GridSearchCV to find the best parameters (kernel, C parameter, Gamma parameter) to train the SVM Model
    - Train the model
    - Evaluate the accuracy and Confusion matrix of the trained model

**Set up and instruction**
1. clone the repository (go to your command prompt)
   - git clone https://github.com/samindika/SVM-Tutorial
   cd SVM-Tutorial
2. Download the notebooks
   - Navigate to the folder where the cloned repository on your local machine.
   - download .ipynb files
3. Open in Google Collab
   -  Go to Google Collab
   -  Click File - Upload Notebook
   -  Upload the .ipynb files downloaded from the cloned folder
4.  Install the necessary libraries
   - In the first code cell of the notebook, run the following command to install the required libraries:
   - !pip install -r requirements.txt
5. Run the notebook
    - Follow the instructions in the notebooks to generate visualizations and reproduce the tutorial results.
