# Parkinsons Telemonitoring Prediction

##  Problem Definition
This is a project to identify a supervised learning problem and perform EDA and model analysis. It is done using Jupyter notebook.
In this case, the problem we will be exploring is **regression analysis**. 

We will use different features about a person to predict their unified Parkinson's disease rating scale (UPDRS). This analysis could be particularly useful because tracking Parkinson's disease (PD) symptom progression often uses unified Parkinson's disease rating scale (UPDRS). Getting the rating scale requires the patient's presence in clinic, and time-consuming physical examinations by trained medical staff. Symptom monitoring is costly and logistically inconvenient for patient and clinical staff alike. 

In a statement,

> Given clinical parameters about a patient, can we predict their unified Parkinson's disease rating scale?

### Dataset Information
The data contains a range of biomedial voice measurements from 42 people with early-stage Parkinson's disease. The dataset is provided by:

Athanasios Tsanas, Max A. Little, Patrick E. McSharry, Lorraine O. Ramig (2009),<br>
'Accurate telemonitoring of Parkinson’s disease progression by non-invasive speech tests',<br>
IEEE Transactions on Biomedical Engineering.

### Data Dictionary
Columns in the table contain subject number, subject age, subject gender, time interval from baseline recruitment date, motor UPDRS, total UPDRS, and 16 biomedical voice measures. Each row corresponds to one of 5,875 voice recording from these individuals. The main aim of the data is to predict the total UPDRS scores ('total_UPDRS') from the 16 voice measures.

The data is in ASCII CSV format. The rows of the CSV file contain an instance corresponding to one voice recording. There are around 200 recordings per patient, the subject number of the patient is identified in the first column. 

Additional information about the variables can be found at https://archive.ics.uci.edu/dataset/189/parkinsons+telemonitoring.
