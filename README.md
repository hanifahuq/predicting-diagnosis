# Predicting Diagnosis and Age

This project aims to find the best-performing models to predict diagnosis (Alzheimer's Disease/ Mild Cognitive Impairment/ Control) and age based on MRI features of brain regions. 

Files:
- `training_validation.csv` : Used to find the best-performing models and combined pipeline. Also used as training data for final pipeline script
- `test.csv` : randomised data to ensure that my final pipeline runs on the same formatted data
- `predictions.csv` : randomised data to ensure that my final pipeline script produces the same format
- `K20002990_InvestigativeScript.ipynb` : Investigative script to find the best-performing models and combined pipeline.
- `K20002990_FinalPipeline.ipynb` : Final pipeline script used to train on `training_validation.csv` and predict age on test MRI data (using real data, witheld from the file)
- `MLN Powerpoint.pptx` : Powerpoint encompassing the background, aims, results, and conclusions

Note: The real test set and predictions were withheld by my professor, which is why I used the 'trainval' data for all investigations, including testing.

Further information about the background, aims and results can be found in the powerpoint presentation.

Methods Graphical Abstract (Completed on the 'trainval' dataset):
![MethodsAbstract](https://github.com/hanifahuq/predicting-diagnosis/assets/109694690/08c7203f-2bb6-40f2-999b-e106096e9e6a)
