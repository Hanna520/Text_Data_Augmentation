Objectives:

This study aims to investigate the effects of 20 text data augmentation methods and different augmentation strategies on the model performance of text classification tasks on unstructured medical notes. 

Data:

The data used in this study were derived from datasets on https://portal.dbmi.hms.harvard.edu/projects/n2c2-nlp/. Although the data are de-identified and publicly available, authorization is required to download the datasets from this website. The data is consisted of 1,237 discharge summary notes that were annotated with 16 disease conditions (Gout, OSA, Gallstones, Hypertriglyceridemia, Depression, Diabetes, Asthma, OA, PVD, CAD, Obesity, Hypertension, Venous, Hypercholesterolemia, GERD, CHF).

How to run the code:

1. Go to https://portal.dbmi.hms.harvard.edu/projects/n2c2-nlp/ and follow the instructions to download the datasets (XML files) and run the Read_XML_Data.ipynb code to read the data. 
2. Download all packages required in the code
3. Change your current working directory accordingly
4. Run the code to generate model performance results
5. Run the R file to create model performance graphs