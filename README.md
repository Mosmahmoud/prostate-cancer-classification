# Project Name 
Prostate Cancer Classification Using ML Model (SVM)


## Tools and Software used
VS Code was used as the main Software program
Python was used as the main programming language 


## Used Libraries 
pandas - numpy - matplotlib - seaborn - sklearn 


# About the Data Used
This project uses a dataset with 569 records and 33 columns, originally derived from the Wisconsin Diagnostic Breast Cancer (WDBC) dataset, though it is being used here for classification modeling techniques applicable to prostate cancer classification tasks.

🧬 Features
Diagnosis: Target variable — M = Malignant, B = Benign.

ID: Unique patient identifier.

30 Numerical Features: Calculated from digitized images of fine needle aspirate (FNA) of a breast mass. These include:

Mean, Standard Error (SE), and Worst (largest) values for:

Radius

Texture

Perimeter

Area

Smoothness

Compactness

Concavity

Concave points

Symmetry

Fractal dimension

Example columns:

radius_mean, texture_mean, ..., radius_se, ..., radius_worst, etc.

🔍 Data Summary
Total samples: 569

Diagnosis breakdown:

M (Malignant): 212

B (Benign): 357

No missing values in features except for one column (Unnamed: 32), which is completely empty and can be safely dropped.

Feature types:

1 categorical (diagnosis)

31 numerical

1 identifier (id)

1 empty column (Unnamed: 32)



## Results
To classify prostate cancer, I used a Support Vector Machine (SVM) classifier. After training the model on the dataset, I evaluated its performance using an accuracy score and a confusion matrix. The accuracy provides an overall measure of how well the model predicts the correct diagnosis, while the confusion matrix offers a deeper insight into the true positives, true negatives, false positives, and false negatives, helping to assess how well the model distinguishes between malignant and benign cases.

![Image](https://github.com/user-attachments/assets/bc8b6f29-f462-4672-934d-2c6939a64281)
![Image](https://github.com/user-attachments/assets/a7ce992c-36a9-4068-9799-e7f041205ba6)




