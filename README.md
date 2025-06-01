**Heart Disease Prediction**

**Overview:**

Heart Disease is an impactful disease, causing over 17 million deaths annually worldwide (approximately 42%) and is one of the leading causes of death globally. Heart Disease refers to a condition where the coronary arteries (which supply blood to the heart muscle) become narrowed, blocked or obstructed. This obstruction has a buildup of fatty deposits, cholesterol, and other substances causing reduced blood flow to the heart. 

Over time, without treatment or intervention, the lack of blood being pumped to the heart can lead to symptoms like chest pain, shortness of breath, or a heart attack that can ultimately lead to death.

This project leverages machine learning models to analyze heart disease data and predict the likelihood of heart disease based on various health and demographic factors. This heart_disease dataset is preprocessed and utilized to train multiple models, including Logistic Regression, Support Vector Machines (SVMs), Neural Networks and Deep Learning (LSTM). 


**Dataset:**

The dataset consists of patient health records, including key features such as:

•	Age (numeric) : representing age, min:28 max:77 scale

•	Sex (binary) : 0 = female or 1 = male

•	ChestPainType (binary):  0 = NAP, ATA for not being related to CHD or 1 = ASY, TA for being related to CHD

•	RestingBP (numeric): blood pressure recording a rest, low < 90 or normal 90 <= 130 or high >= 130 and above

•	Cholesterol (binary): 0 = 0 - 240 for normal or 1 = 241 - 603 for high

•	FastingBS (binary): 0 = normal fasting blood sugar or 1 = high fasting blood sugar

•	RestingECG (categorical): Electrocardiogram (ECG) results, LVH or Normal or ST

•	MaxHR (numeric): maximum heart rate reached, 0 = min heart rate or 1 = max heart rate  

•	ExerciseAngina (binary): 0 = angina not induced by exercise or 1 = angina induced by exercise 

•	Oldpeak (numeric): observed ECG results, downward shift in the ST segment, min:-2.6 max:6.2 scale

•	ST_Slope (binary): 0 = Up or 1 = Down, Flat

•	HeartDisease (binary): 0 = absence of heart disease or 1 = presence of heart disease (Target variable) 



**Models Utilized:**

The project implements various machine learning models to compare their predictive performance:

•	Logistic Regression

•	Support Vector Machine (SVM)

•	Neural Network 

•	Deep Learning (LSTM)


**Installation:**

To set up and run the project locally:
1.	Clone the repository
2.	Navigate to the project directory
3.	Install dependencies



**Usage:**

• Run the model training and evaluation

• Visualize the various models mentioned above for performance comparison



**Results:**

The models' performance shows the trade-off between sensitivity of a true positive rate and specificity of a false positive rate. According the metrics examined, the SVM model is the best-performing model.

Despite the current study’s findings, there is ample room for future research.


**Contributors:**

**Brittani Borroto**
