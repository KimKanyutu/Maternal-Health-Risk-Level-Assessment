# Maternal-Health-Risk-Assessment
This repository is a basic data science project to classify the risk level of expectant mothers based on a number of vitals recorded using IoT devices.

Data has been collected from different hospitals, community clinics, maternal health cares from the rural areas of Bangladesh through the IoT based risk monitoring system.
The vitals that we will be working with include;

1. Age, 
2. Systolic Blood Pressure as SystolicBP, 
3. Diastolic BP as DiastolicBP, 
4. Blood Sugar as BS, 
5. Body Temperature as BodyTemp, 
6. HeartRate

Based on these vitals, we can predict the risk level of the mother and hence associate it with the necessary attention

|AttributeName| Role	  | Type	      |Description	|
|:---         | :---:   | :---:       |   ---:|
| Age	        | Feature |	Integer     |	Any ages in years when a woman during pregnant.|
| Systolic_BP	| Feature |	Integer	    |	Upper value of Blood Pressure in mmHg, another significant attribute during pregnancy.|
| Diastolic_BP| Feature |	Integer	    |	Lower value of Blood Pressure in mmHg, another significant attribute during pregnancy.|
| Blood_Sugar	| Feature	| Integer     |	Blood glucose levels is in terms of a molar concentration.(mmol/L)|
| BodyTemp	  | Feature	| Integer	    |	Degrees Celsius	|
| Heart_Rate	| Feature	| Integer	    |	A normal resting heart rate.(bpm)|
| Risk_level	| Target	| Categorical	|	Predicted Risk Intensity Level during pregnancy considering the previous attribute.|

## Dataset
[Download Dataset here!](https://archive.ics.uci.edu/static/public/863/maternal+health+risk.zip)

## Reference
Ahmed,Marzia. (2023). Maternal Health Risk. UCI Machine Learning Repository. https://doi.org/10.24432/C5DP5D.
