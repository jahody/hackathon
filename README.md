# AI HACKATHON
My role was to prepare dataset for the competition (notebook 1) and check if the task was feasible (notebooks 2 and 3).

### DATA
Labeled train data set of reminder communication history for dental appointments. 
Each reminder gives a patient option to confirm the appointment.
Data has approximately 20 variables with information about appointments, reminders, clinics and patients from all over Canada.

### TASK
Predict if a certain reminder led to confirmation of an appointment.

### NOTEBOOKS
1-data.ipybn  - data gathering, cleaning, feature engineering

2-eda.ipybn   - exploratory data analysis over the train set

3-model.ipybn - deep learning model, fast.ai library, google colab platform


### EVALUATION
The percentage of appointment confirmations correctly predicted from test set.


I was able to predict with 70% accurancy if a certain reminder led to confirmation of an appointment.
I also tested the model for a potential deployment - to see what type of reminder at which time led to the highest probability of confirmation.
