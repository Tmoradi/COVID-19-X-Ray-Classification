# COVID-19-X-Ray-Classification

**Goal** : Given 2 dimensional X-ray image data, to develop models for both binary and multi-class classification.
Included in the repository is the report written for this project. It dives further into my reason for Model Selection, Hyperparameter Tuning, and thought process.

## Data
The data that was used for this project was a combination of the Kaggle Chest X-ray dataset with the COVID-19 Chest X-ray dataset that was curated by Dr. Joseph Paul Cohen from the University of Montreal
Here is a link to access the [data](https://drive.google.com/file/d/1Y88tgqpQ1Pjko_7rntcPowOJs_QNOrJ-/view)

The work has been divided into two notebooks, task1.ipynb and task2.ipynb

**Task1** contains the Binary Classification between COVID-19 X-rays and Normal Patients.
**Task2** contains Multi-Class Classification between COVID-19, Normal, pneumonia_bac, pneumonia_vir.

## Results

For task1, using VGG19 as the base model for Transfer Learning, model was able to achieve 89 percent test accuracy. 

For task2, models VGG19 and DenseNet only achieved 66 percent test accuracy.
