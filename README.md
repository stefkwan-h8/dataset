# dataset

# Canada.xlsx
diambil dari https://www.un.org/en/development/desa/population/migration/data/empirical2/migrationflows.asp ini merupakan dataset tentang imigrasi ke Canada sejak tahun 1980 hingga tahun 2013.

# heart.csv
diambil dari https://www.kaggle.com/ronitf/heart-disease-uci ini merupakan dataset tentang orang yang ke rumah sakit, tes darah, punya keluhan sakit dada, dan di diagnosa punya sakit jantung atau tidak.   

beberapa kolomnya:
- age (umur)
- sex (gender, 1 = Pria, 0 = Wanita)
- chest pain type (tipe sakit di dada, ada 4 jenis)
- resting blood pressure (tekanan darah dalam mm Hg saat masuk rumah sakit)
- serum cholestoral in mg/dl (tingkat kolesterol dalam mg/dl)
- fasting blood sugar > 120 mg/dl (tingkat gula darah >= 120 mg/dl, 1 = ya, 0 = tidak)
- resting electrocardiographic results (hasil tes dcg untuk lihat ritme jantung, ada 3 jenis hasil 0,1,2)
- maximum heart rate achieved (maximum detak jantung)
- exercise induced angina (merasakan sakit dada saat olahraga? 1 = ya, 0 = tidak)

# housing_london.csv
diambil dari https://www.kaggle.com/justinas/housing-in-london ini merupakan dataset tentang harga rumah di London

# stroke.csv
diambil dari https://www.kaggle.com/fedesoriano/stroke-prediction-dataset merupakan dataset tentang pasien stroke (0 tidak pernah, 1 pernah stroke)

# weatherAUS.csv
diambil dari https://www.kaggle.com/jsphyg/weather-dataset-rattle-package ini merupakan dataset tentang cuaca di Australia, digunakan untuk memprediksi apakah besok hujan atau tidak.

# Student Alcohol
About Dataset
Context:
The data were obtained in a survey of students math and portuguese language courses in secondary school. It contains a lot of interesting social, gender and study information about students. You can use it for some EDA or try to predict students final grade.

Content:
Attributes for both student-mat.csv (Math course) and student-por.csv (Portuguese language course) datasets:

school - student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
sex - student's sex (binary: 'F' - female or 'M' - male)
age - student's age (numeric: from 15 to 22)
address - student's home address type (binary: 'U' - urban or 'R' - rural)
famsize - family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)
Pstatus - parent's cohabitation status (binary: 'T' - living together or 'A' - apart)
Medu - mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
Fedu - father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
Mjob - mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
Fjob - father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
reason - reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')
guardian - student's guardian (nominal: 'mother', 'father' or 'other')
traveltime - home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
studytime - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
failures - number of past class failures (numeric: n if 1<=n<3, else 4)
schoolsup - extra educational support (binary: yes or no)
famsup - family educational support (binary: yes or no)
paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
activities - extra-curricular activities (binary: yes or no)
nursery - attended nursery school (binary: yes or no)
higher - wants to take higher education (binary: yes or no)
internet - Internet access at home (binary: yes or no)
romantic - with a romantic relationship (binary: yes or no)
famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
freetime - free time after school (numeric: from 1 - very low to 5 - very high)
goout - going out with friends (numeric: from 1 - very low to 5 - very high)
Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
health - current health status (numeric: from 1 - very bad to 5 - very good)
absences - number of school absences (numeric: from 0 to 93)
These grades are related with the course subject, Math or Portuguese:

G1 - first period grade (numeric: from 0 to 20)
G2 - second period grade (numeric: from 0 to 20)
G3 - final grade (numeric: from 0 to 20, output target)
Additional note: there are several (382) students that belong to both datasets .
These students can be identified by searching for identical attributes
that characterize each student, as shown in the annexed R file.

https://www.kaggle.com/datasets/uciml/student-alcohol-consumption
https://archive.ics.uci.edu/ml/datasets/STUDENT+ALCOHOL+CONSUMPTION
