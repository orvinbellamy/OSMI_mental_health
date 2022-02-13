# OSMI_mental_health

Contributors: Orvin Bellamy, Isha Goyal, Elodie Garguilo

This is a Machine learning model to predict interference of mental health conditions at work according to employee and company profile. Dataset sourced from OSMI.
https://www.kaggle.com/osmi/mental-health-in-tech-survey
https://osmihelp.org/about/about-osmi

Refer to the Kaggle page for the data dictionary

This project is done using Python 3.8.8, note that some errors were encountered when executed using Python 3.9

This machine learning model is used to predict whether employees' mental health conditions interfere with their work based on OSMI's survey filled by employees. Features derived from the employee's and company's profile are used against the 'work_interfere' variable as label.

Note that given the small dataset size, labels classes have to be collapsed into 2 (binary) classes. More information about data preprocessing can be read below.

Some data discoveries and visualziation is done via simple Tableau bar charts available as a Tableau Workbook & .ppt file in this git.

Please refer to the notes and comments in the main.ipynb for further explanations.

Files:
- main.ipynb --> main Jupyter Notebook
- survey.csv --> dataset from https://www.kaggle.com/osmi/mental-health-in-tech-survey
- EDA.ppt --> graphs for data exploration
- EDA.twbx, EDA.twb, 'df (df).hyper' --> Tableau workbook used to create graphs for data explration
