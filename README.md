--- PAGE 1 ---

[cite_start]HEART DISEASE PREDICTION AND IDENTIFICATION WITH DEEP LEARNING AND NEURAL NETWORKS [cite: 1]
[cite_start]BY KOTESWAR ENAMADNI [cite: 2]
[cite_start]PROPOSAL [cite: 3]
[cite_start]Heart-related diseases are among the most widely recognized reasons for death around the world[cite: 4]. [cite_start]Patients are frequently asymptomatic until a deadly occasion occurs, and in any event, when they are under perception, a prepared workforce is required to recognize a heart abnormality[cite: 5]. [cite_start]Somewhat recently, there has been expanding proof of how deep learning can be utilized to recognize such oddities, because of the accessibility of Electrocardiograms (ECG) in computerized design[cite: 6]. [cite_start]New advancements in innovation have permitted us to take advantage of such information to fabricate models ready to dissect the examples in the event of heartbeats, and spot abnormalities from them[cite: 7]. [cite_start]In this work, master cardiologists across various clinics and nations can recognize 7 sorts of signs: Typical, AF, Tachycardia, Bradycardia, Arrhythmia, Other, or Boisterous [cite: 8][cite_start]. [cite: 9]
[cite_start]The determination of heart illness has turned into a troublesome clinical errand in the current clinical examination[cite: 10]. [cite_start]This finding relies upon the point-by-detailed and exact examination of the patient's clinical test information on a singular's well-being history[cite: 11]. [cite_start]The huge improvements in the field of profound learning look to make astute mechanized frameworks that help specialists anticipate and decide the illness with the web of things with Deep learning[cite: 12]. [cite_start]Certainty adjustment is a particularly important issue in a medical care setting like the one tended to in this composition: when a neural network model makes an expectation, it is vital that this result can be relied upon [cite: 13][cite_start]. [cite: 14]
[cite_start]The Deep learning algorithm will be applied in the prediction of heart disease with a different types of attributes with the dataset[cite: 15].

--- PAGE 2 ---

[cite_start]Objective: [cite: 16]
[cite_start]The objective of heart disease identification with deep learning is to detect heart disease in the early stage itself with the available attributes[cite: 17]. [cite_start]In this work, the dataset containing heart disease will be taken into consideration[cite: 18]. [cite_start]The pre-processing will be applied to the dataset, and the noisy and null value data will be removed[cite: 19]. [cite_start]After the data will be analyzed and visualized for further processing[cite: 20]. [cite_start]The Deep learning algorithm will be chosen to make the prediction[cite: 21]. [cite_start]The dataset will be divided into two parts[cite: 22]. [cite_start]The first part of the dataset is 70% taken to provide training to the Deep learning algorithm and the remaining 30% of data is taken to the testing part[cite: 22].
[cite_start]Motivation: [cite: 23]
[cite_start]Deep learning will be the Python-based application that contributes to finding out the heart disease's early stage[cite: 24]. [cite_start]It will be helpful for humans to detect it early and to take the necessary treatments at the correct time[cite: 25].
[cite_start]Significance: [cite: 26]
[cite_start]The project evaluation can be tested with the deep learning algorithm prediction results[cite: 27]. [cite_start]Since the Deep learning algorithm will be used to predict the disease, the accuracy of the algorithm result will be helpful to evaluate the results [cite: 28][cite_start]. [cite: 29] [cite_start]The accuracy score of the algorithm in heart disease identification helps to evaluate the dataset[cite: 29]. [cite_start]The application will be developed with Google Colab Python Tool as the project can be directly executed in any type of computer system with an internet connection[cite: 30]. [cite_start]There is no need for any specific software to be installed in the user system[cite: 31]. [cite_start]The Colab Tool helps to develop and run the application directly inside the cloud server where the Python library files [cite: 32]

--- PAGE 3 ---

[cite_start]are installed[cite: 33]. [cite_start]The deep learning algorithm libraries are built inside the Colab[cite: 33]. [cite_start]It helps the project to use the deep learning algorithm in the finding of heart disease[cite: 34].
[cite_start]INCREMENT [cite: 35]
[cite_start]Techniques Applied: [cite: 36]
[cite_start]The task included the examination of the heart disease patient dataset with appropriate information handling[cite: 37]. [cite_start]Then, at that point, various models were prepared and expectations are made with the Deep Learning model[cite: 38]. [cite_start]The machine learning library and deep learning libraries Sklearn and Keras are applied to the application[cite: 39].
[cite_start]Dataset: [cite: 40]
[cite_start]Most of the columns in a dataset are noisy and contain lots of information[cite: 41]. [cite_start]But with feature engineering, will get more good results[cite: 42]. [cite_start]The first step is to import the libraries and load data[cite: 42]. [cite_start]After that will take a basic understanding of data like its shape, sample, is there any NULL values present in the dataset[cite: 43]. [cite_start]Understanding the data is an important step for prediction or any Deep learning project[cite: 44]. [cite_start]It is good that there are no NULL values[cite: 45]. [cite_start]The dataset heart.csv is downloaded from the Kaggle website, it has 300 rows and 14 columns present[cite: 46].

--- PAGE 4 ---

[cite_start]Detailed Design of Features: [cite: 47]
[cite_start]This dataset contains the fields needed for the analysis of the heart disease dataset[cite: 48]. [cite_start]The exploratory examination is a cycle to investigate and comprehend the information and information related in a total profundity with the goal that it makes highlight designing and Deep Learning demonstrating steps smoothly and smoothed out for expectation[cite: 49]. [cite_start]The exploratory examination assists with validating our presumptions or misleading[cite: 50].

[cite_start]The following table: [cite: 51]
"Copy
",,"Calibri
",,"AA
",,,"Wrap Text
","General
",,,,"zon
",
"Puste


Format Painter


Optoma
",,"B
",," 
",,,"Merge Center
",,"A
","Conditional Format Cel
 Formatting as Table Styles
 Dy
",,"Sort & Find
 2 Clear
 Filter Select
 Editing


Inseit Delete Format
",
"A1
",,,"age
",,,,,,,,,,
"B
",,,"C
 D
 E
","F
","G
",,"H
",,,"L
 M
 K
 N
",,"T


R


0
 P
 Q


S
","0
"
"1 age
 12


sex
",,"cp
","trestops
","chol


fbs
","restecg
",,"thalach exang
","oldpeak slope
","Cá
","thal


target
",,,
"2


63
","1
","3
","145
","233
","1
","0
","150


0
","2.3
",,"0


1
","1
",,
"37


3
","1
","2
","130
","250
","0
","1
","187


0
","3.5
","0
","0


2


1
",,,
"41


4
","0
","1
","130
","204
","0
","0
","0


172
","14
","2
","0


2


1
",,,
"56


3
","1
","1
","120
","236
","0
","1
","178


0
","0.8
","2
","1


2


0
",,,
"57
","0
","0
","120
","354
","0
","1
","163


1
","0.6
","2
","0


2


1
",,,
"57


7
","1
","0
","140
","192
","0
","1
","148


0
","04
","1
","0


1
","1
",,,
"56
",,"1
","140
","294
","0
",,"153


0
","13
","1
","2


0
",,,
"44
","1
","1
","120
","263
","0
","1
","173


0
","0
","2
","3


0
","1
",,
"10


52
","1
","2
","172
","199
","1
","1
","162


0
","0.5
","2
","0


3
","1
",,
"57


11
","1
","2
","150
","168
","0
","1
","174


0
","1.6
","2
","0


2
","1
",,
"54


12
","1
","0
","140
","239
","0
","1
","160


0
","1.2
","2
","0


2
","1
",,
"48


13
","0
","2
","130
","275
","0
","1
","139


0
","0.2
","2
","0


1
","2
",,,
"14


49
","1
","1
","130
","266
","0
","1
","171


0
","0.5
","2
","0


2
","1
",,
"15


64
","1
","3
","110
","211
","0
","0
","144


1
","18
","1
","0


2
","1
",,
"58


16
","0
","3
","150
","283
","1
","0
","162


0
",,"2
","0


1
","2
",,,
"50


17
","0
","2
","120
","219
","0
","1
","158


0
","1.6
","1
","2


1
","0
",,,
"18


58
",,"2
","120
","340
","0
","1
","172


0
","0
","2
","0


2
","1
",,
"66


19
","0
","3
","150
","226
","0
","1
","114


0
","2.6
","0
","0


2
","1
",,
"43


20
","1
","0
","150
","247
","0
","1
","171


0
","15
","2
","0


1
","2
",,,
"21


69
",,"3
","140
","239
","0
","1
","151


0
","18
","2
","2


2
","1
",,
"22


59
","1
","0
","135
","234
","0
","1
","161


0
","0.5
","1
","0


3
","1
",,
"44


23
","1
","2
","130
","233
","0
","1
","179


1
","04
","2
","0


2
","1
",,
"42


24
","1
","0
","140
","225
","0
","1
","178


0
","0
","2
","0


2
","1
",,
"25


61
","1
","2
","150
","243
","1
","1
","137


1
","1
","1
","2


0
","1
",,,

--- PAGE 5 ---

[cite_start]Analysis of Heart Disease Prediction: [cite: 52]
[cite_start]It will begin from the principal segment and investigate every section and comprehend what influence it makes on the objective segment[cite: 53]. [cite_start]At the necessary step, we will likewise perform preprocessing and include design undertakings[cite: 54]. [cite_start]The point in acting top-to-bottom exploratory examination is to get ready and clean information for better Deep Learning demonstrating to accomplish elite execution and summed up models[cite: 55]. [cite_start]So it should begin with breaking down and setting up the dataset for expectation[cite: 56].
[cite_start]Modules: [cite: 57]
[cite_start]1) Dataset collection [cite: 58]
[cite_start]2) Data cleaning [cite: 59]
[cite_start]3) Data Analysis [cite: 60]
[cite_start]4) Deep learning Modeling [cite: 61]
[cite_start]5) Report [cite: 62]
[cite_start]1) Dataset collection: [cite: 63]
[cite_start]The information about the heart disease dataset with different types of attributes are collected [cite: 64] [cite_start]from different type of patients[cite: 65].

--- PAGE 6 ---

[cite_start]2) Data Cleaning: [cite: 66]
[cite_start]The large dataset contains more noisy and improper data which have to be pre-processed to produce a quality dataset for further pruning[cite: 67]. [cite_start]The data is cleaned and processed with the initial stage of removing the null values[cite: 68].
[cite_start]3) Data Analysis [cite: 69]
[cite_start]Exploratory analysis is a process to explore and understand the data and data relationship in complete depth so that it makes feature engineering and machine learning modeling steps smooth and streamlined for prediction[cite: 70]. [cite_start]It helps to prove our assumptions true or false[cite: 71]. [cite_start]In other words, it helps to perform hypothesis testing[cite: 71].
[cite_start]4) Deep learning Modeling [cite: 72]
[cite_start]Deep learning modeling helps to find the best algorithm with the best hyperparameters to achieve maximum accuracy[cite: 73]. [cite_start]The dataset is split into 2 variants[cite: 74]. [cite_start]70% of records are taken as training data and used to train the machine learning algorithm[cite: 74]. [cite_start]The remaining 30% of the dataset is applied to testing which helps to predict the process[cite: 75].
[cite_start]5) Report: [cite: 76]
[cite_start]The Data is visualized based on the output of the Deep Learning algorithm and the data is mapped with different types of graphs to analyze and visualize the exact data to the user for the prediction[cite: 77]. [cite_start]Matplot libraries are implemented to map the results based on user requirements[cite: 78].

--- PAGE 7 ---

[cite_start]SYSTEM SPECIFICATION [cite: 79]
[cite_start]HARDWARE REQUIREMENTS [cite: 80]
[cite_start]Processor [cite: 81]
[cite_start]Clock Speed RAM [cite: 82]
[cite_start]Hard Disk [cite: 83]
[cite_start]Monitor [cite: 84]
[cite_start]• Mouse [cite: 85]
[cite_start]Keyboard [cite: 86]
[cite_start]Display Card [cite: 87]
[cite_start]Intel(R) Pentium(R) CPU G2010 @ 2.80GHz [cite: 88]
[cite_start]2.00 GB [cite: 89]
[cite_start]1 TB HDD [cite: 90]
[cite_start]15.6 Inches [cite: 91]
[cite_start]Logitech B100 Wired Optical Mouse [cite: 92]
[cite_start]Full-size island-style keyboard with number keypad [cite: 93]
[cite_start]Super Video Graphics Adapter [cite: 94]
[cite_start]SOFTWARE REQUIREMENTS [cite: 95]
[cite_start]Operating System: [cite: 96]
[cite_start]Front-End Tool: [cite: 97]
[cite_start]Windows 10 [cite: 98]
[cite_start]Python in Google Colab [cite: 99]

--- PAGE 8 ---
