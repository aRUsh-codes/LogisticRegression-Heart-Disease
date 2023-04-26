# Predicting Heart-Disease using Logistic Regression
 This research intends to pinpoint the most relevant/risk factors of heart disease as well as predict the overall risk using logistic regression.
The dataset, which is publicly accessible on the Kaggle platform, comes from an ongoing cardiovascular research of people living in the Massachusetts town of Framingham. The classification objective is to identify a patient's 10-year risk of developing coronary heart disease (CHD).Information about the patients is provided by the dataset. It has 15 qualities and more than 4,000 records.

##Variables :
Each attribute is a potential risk factor. There are both demographic, behavioural and medical risk factors.

##Demographic: 

#sex: male or female;(Nominal)

#age: age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)
Behavioural:

#currentSmoker: whether or not the patient is a current smoker (Nominal)

#cigsPerDay: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarretts, even half a cigarette.)

##Medical( history):

#BPMeds: whether or not the patient was on blood pressure medication (Nominal)

#prevalentStroke: whether or not the patient had previously had a stroke (Nominal)

#prevalentHyp: whether or not the patient was hypertensive (Nominal)

#diabetes: whether or not the patient had diabetes (Nominal)

##Medical(current):

#totChol: total cholesterol level (Continuous)

#sysBP: systolic blood pressure (Continuous)

#diaBP: diastolic blood pressure (Continuous)

#BMI: Body Mass Index (Continuous)

#heartRate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)

#glucose: glucose level (Continuous)

##Predict variable (desired target):

10 year risk of coronary heart disease CHD (binary: “1”, means “Yes”, “0” means “No”)
