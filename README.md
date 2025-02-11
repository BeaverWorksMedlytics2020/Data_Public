# Datasets
## diabetes.csv
This data table was taken from the [Pima Indians Diabetes Dataset on Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database). All patients here are females at least 21 years old of Pima Indian heritage.

- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration 2 hours in an oral glucose tolerance test
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: A function that scores the likelihood of diabetes based on family history.
- **Age**: Age (years)
- **Outcome**: 1 (has diabetes) or 0 (no diabetes)

## Depression_data.csv
This data table uses data from [UFHealth’s Biostatistics Open Learning Textbook](http://bolt.mph.ufl.edu/2012/08/02/learn-by-doing-exploring-a-dataset) but has been artificially biased for the purposes of teaching propensity score matching. In a study conducted by the National Institutes of Health, 109 clinically depressed patients were separated into three groups, and each group was given one of two active drugs (imipramine or lithium) or no drug at all. For each patient, the dataset contains the **treatment used (Treat)**, the **Outcome** of the treatment, and several other characteristics (**Hospt, AcuteT, Age, Gender**).

- **Hospt**: The patient’s hospital, represented by a code for each of the 5 hospitals (1, 2, 3, 5, or 6)
- **Treat**: The treatment received by the patient (Lithium, Imipramine, or Placebo)
- **Outcome**: Whether or not a recurrence occurred during the patient’s treatment (Recurrence or No - Recurrence)
- **AcuteT**: The time (days) that the patient was depressed prior to the study.
- **Age**: The age of the patient in years, when the patient entered the study.
- **Gender**: The patient’s gender (1 = Female, 2 = Male)

## allhypo.train.data.csv, allhypo.test.data.csv
This is the hypothyroidism data set for Week 1’s challenge, taken from [UC Irvine’s Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/thyroid+disease). The table includes 29 attributes for 2800 patients.

- Numerical Columns: Age, TSH, T3, TT4, T4u, FTI
- Categorical Columns: lithium, TT4 measured, psych, query hypothyroid, thyroid surgery, on thyroxine, on antithyroid medication, tumor, TSH measured, FTI measured, query hyperthyroid, sick, pregnant, referral source, Sex

## week2_conv1d
This dataset was taken from [UC Irvine’s Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones) that contains recordings of 30 subjects performing 6 daily activities (**WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING**) while carrying a waist-mounted smartphone with embedded inertial sensors. The data provides the **body acceleration (body_acc_x/y/z), general acceleration (total_acc_x/y/z), and a gyroscope reading (body_gyro_x/y/z)** at a constant rate of 50Hz.


## WisconsinEmployment.csv
Table with time series data on [employment in Wisconsin](https://datamarket.com/data/set/22l8/wisconsin-employment-time-series-trade-jan-1961-oct-1975#!ds=22l8&display=line) from 1961-1975, used in notebook 05 in Week 2 for teaching smoothing/interpolating and filtering.

- **Date**: Year and month
- **Value**: Employment #s

## Week2_Challenge
The 2018 [PhysioNet/CinC (Computing in Cardiology) Challenge](https://www.physionet.org/challenge/) focused on sleep, particularly the classification of nonarousal and arousal timeframes. This dataset is a modified version of the PhysioNet/CinC Challenge data which were contributed by MGH’s Computational Clinical Neurophysiology Laboratory, and the Clinical Data Animation Laboratory. Each sample consists of **seven physiological signals (O2-M1, E1-M2, Chin1-Chin2, ABD, CHEST, AIRFLOW, ECG)** measured at 200Hz over a 60 second period (12000 timepoints).

- **O2-M1**: An EEG derivation that records alpha rhythm (posterior brain activity).
- **E1-M2**: An EEG derivation that records left eye activity (electrooculography).
- **Chin1-Chin2**: Chin movement (electromyography).
- **ABD**: Abdominal movement (electromyography).
- **CHEST**: Chest movement (electromyography).
- **AIRFLOW**: Respiratory airflow.
- **ECG**: Cardiac activity (electrocardiography).

## data_nuclei
Contains cell images for Week 3’s lesson notebooks. This [data set](http://dx.doi.org/10.5281/zenodo.53169) represents a collection of textures in histological images of human colorectal cancer, storing 5000 150x150 images.

## Data_week3_challenge
This folder contains the labels and images for Week 3’s challenge. In this challenge students classify segments of mammogram images as 0 (negative for abnormality) or 1 (positive for abnormality) or 0, 1, 2, 3, 4 in the multiclass problem (negative and varying types of abnormalities). Mammogram images are from the Digital Database for Screening Mammography ([DDSM](http://marathon.csee.usf.edu/Mammography/Database.html)) and the Curated Breast Imaging Subset of DDSM ([CBIS-DDSM](https://wiki.cancerimagingarchive.net/display/Public/CBIS-DDSM)). Jpegs and labels were extracted from a tfrecords dataset on [Kaggle](https://www.kaggle.com/skooch).
