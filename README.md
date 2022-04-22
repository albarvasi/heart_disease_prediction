# heart_disease_prediction
The project implemented performs prediction based on the below features - 
- Age
- Sex
- Chest pain type (4 values)
— Value 0: typical angina
— Value 1: atypical angina
— Value 2: non-anginal pain 
— Value 3: asymptomatic
- trestbps: resting blood pressure (in mm Hg on admission to the hospital)
- chol: serum cholestoral in mg/dl
- fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
- restecg: resting electrocardiographic results
— Value 0: normal
— Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
— Value 2: showing probable or definite left ventricular hypertrophy by Estes’ criteria
- thalach: maximum heart rate achieved
- exang: exercise induced angina (1 = yes; 0 = no)
- oldpeak = ST depression induced by exercise relative to rest

- slope: the slope of the peak exercise ST segment
— Value 1: up-sloping
— Value 2: flat
— Value 3: down-sloping
- ca: number of major vessels (0–3) colored by fluoroscope
- thal: 3 = normal; 6 = fixed defect; 7 = reversible defect
Logistic Regression, Random Forest Classifier and Gradient Boosting Classifier are the algorithms that have been implemented, from which Random Forest Classifier provides the best accuracy.
We have implemented the final model using Random Forest Classifier.
Tkinter model of python is used for implementing the GUI of the project.
