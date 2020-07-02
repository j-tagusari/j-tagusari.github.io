環境衛生工学特論サンプルデータセット
このデータセットは，以下URLに提供されたデータセットを一部修正したものです．
解析にあたっては，以下の内容をよく確認してください．
2019.6.11 Junta Tagusari

Source:
 URL: 
 https://archive.ics.uci.edu/ml/datasets/heart+Disease
 http://archive.ics.uci.edu/ml/datasets/statlog+(heart)

Creators:
 1. Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
 2. University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
 3. University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
 4. V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.

Donor:
 David W. Aha (aha '@' ics.uci.edu) (714) 856-8779

Data Set Information:

 This database contains 13 attributes (which have been extracted from a larger set of 75). In particular, the Cleveland database is the only one that has been used by ML researchers to this date. The goal is to evaluate the contributions of the factors to the risks of heart disease in the patient. 
 There are 270 observations with no missing values.


Attribute Information:
1. age: age in years
2. sex: sex
 Value 0: female
 Value 1: male
3. cp: chest pain type 
 Value 1: typical angina
 Value 2: atypical angina
 Value 3: non-anginal pain
 Value 4: asymptomatic
4. sbp: systolic blood pressure (in mm Hg on admission to the hospital) 
5. chol: serum cholestoral in mg/dl 
6. fbs: (fasting blood sugar > 120 mg/dl)  
 Value 0: fbs <= 120 mg/dl
 Value 1: fbs >  120 mg/dl
7. restecg: resting electrocardiographic results
 Value 0: normal
 Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
 Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria 
8. mthalach: maximum heart rate achieved 
9. exang: exercise induced angina
 Value 0: no
 Value 1: yes
10. oldpeak: ST depression induced by exercise relative to rest 
11. slope: the slope of the peak exercise ST segment
 Value 1: upsloping
 Value 2: flat
 Value 3: downsloping 
12. ca: number of major vessels (0-3) that appeared to contain calcium colored by flourosopy 
13. thal: excercise thallium scintigraphic defects
 Value 3: normal
 Value 6: fixed defect
 Value 7: reversable defect 
14. hd: absence or presence of heart disease
 Value 1: absence
 Value 2: presence

Attributes types:
 Real: 1,4,5,8,10,12
 Ordered:11,
 Binary: 2,6,9
 Nominal:7,3,13