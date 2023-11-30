# Sleep_disorder_prediction

## Problem Statement
The aim of the project is to analyze the person's lifestyles and medical variables such as age, BMI, physical activity, sleep duration, blood pressure and many more, to predict the sleep disorder and its type.

![image](https://github.com/hemanthm01/Sleep_disorder_prediction/assets/120650945/557f08f4-d4cf-4594-ab29-46e0cd81c3ee)

## About the Dataset
The Sleep Health and Lifestyle Dataset comprises 400 rows and 13 columns, covering a wide range of variables related to sleep and daily habits. It includes details such as gender, age, occupation, sleep duration, quality of sleep, physical activity level, stress levels, BMI category, blood pressure, heart rate, daily steps, and the presence or absence of sleep disorders.

## Key Features of the Dataset:
Comprehensive Sleep Metrics: Explore sleep duration, quality, and factors influencing sleep patterns.
Lifestyle Factors: Analyze physical activity levels, stress levels, and BMI categories.
Cardiovascular Health: Examine blood pressure and heart rate measurements.
Sleep Disorder Analysis: Identify the occurrence of sleep disorders such as Insomnia and Sleep Apnea.
Data Dictionary
Column Name	Description
Person_ID	Unique ID assigned to each person
Gender	The gender of the person (Male/Female)
Age	Age of the person in years
Occupation	The occupation of the person
Sleep_duration	The duration of sleep of the person in hours
Quality_of_sleep	A subjective rating of the quality of sleep, ranging from 1 to 10
Physical_activity	The level of physical activity of the person (Low/Medium/High)
Stress Level	A subjective rating of the stress level, ranging from 1 to 10
BMI_category	The BMI category of the person (Underweight/Normal/Overweight/Obesity)
Blood_pressure	The blood pressure of the person in mmHg
Heart_rate	The heart rate of the person in beats per minute
Daily Steps	The number of steps taken by the person per day
Sleep_disorder	The presence or absence of a sleep disorder in the person (None, Insomnia, Sleep Apnea)
Details about Sleep Disorder Column:
None: The individual does not exhibit any specific sleep disorder.
Insomnia: The individual experiences difficulty falling asleep or staying asleep, leading to inadequate or poor-quality sleep.
Sleep Apnea: The individual suffers from pauses in breathing during sleep, resulting in disrupted sleep patterns and potential health risks.

## Conclusion
From the exploratory data analysis, I have concluded that the sleep orders depends upon three main factors that are gender, occupation and BMI of the patient. The males have more instance of Insomia whereas femlaes have more instances of Sleep Apnea. In addition the that people with occupation such as nurses are more prone to sleep disorders. The BMI of the patient also plays a vital role in the prediction of sleep disorders. The patients who are either Obese or overweight are more prone to sleep disorders.

Coming to the classfication models, both the models performed pretty good, however the Random Forest Classifier have excellent results with 89% accuracy. Decision Tree has 87% accuracy.

