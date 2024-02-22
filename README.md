# Vehicle-Insurance-Fraud-Detection
Vehicle Insurance Claim Fraud Detection
![Fraud-Detection](https://github.com/VIJAY84SH/Vehicle-Insurance-Fraud-Detection/assets/95535340/adfc5058-a4fd-43eb-8f5b-d9ba8f8f5806)

Vehicle insurance fraud involves conspiring to make false or exaggerated claims involving property damage or personal injuries following an accident. Some common examples include staged accidents where fraudsters deliberately “arrange” for accidents to occur; the use of phantom passengers where people who were not even at the scene of the accident claim to have suffered grievous injury, and make false personal injury claims where personal injuries are grossly exaggerated

# 𝐎𝐛𝐣𝐞𝐜𝐭𝐢𝐯𝐞
The objective is to classify claims as fraud or non-fraud, so we don't have to waste time to analyse every claim by assigning specialists

# 𝐆𝐨𝐚𝐥
The goal is to develop and implement a fraud detection system that leverages advanced technologies such as data analytics, machine learning algorithms, and predictive model

# 𝐄𝐃𝐀
# Primary Analysis
From the pie plot, we understand that this dataset is imbalanced, that means we don't have enough samples from each
class and we will have problems to train the model, so we have to balance this dataset before training the model. We do

this in the data preprocessing section

The amount of claims in different months does not differ so much that we can find out a special point from it
Top 5 Make of claims in order is:

1.Pontiac (Highest)
2.Toyota
3.Honda
4.Mazda
5.Chevrole

Most accidents occur in Urban areas and the remaining occur in Rural areas.
Most driver are men and than women
Most of the frauds are in age of 26 to 45

# 𝐂𝐋𝐀𝐒𝐒 𝐈𝐌𝐁𝐀𝐋𝐀𝐍𝐂𝐄
 Handling Class Imbalance using SMOTE
SMOTE is a popular technique used in machine learning to address class imbalance by generating synthetic samples for the minority class.
It works by creating synthetic instances of the minority class by interpolating between existing minority class instances.
This method helps in balancing the class distribution, making the dataset more suitable for training models.

# 𝐀𝐝𝐯𝐚𝐧𝐭𝐚𝐠𝐞𝐬:
 1. Insurance company no need to assign specialists
 2. Save cost and time 
 3. Reduce financial burden of fraudulent claims

 # 𝐃𝐢𝐬𝐚𝐝𝐯𝐚𝐧𝐭𝐚𝐠𝐞:
 Recall score for class1 is less so some claim can not be detected

 # 𝐂𝐨𝐧𝐜𝐥𝐮𝐬𝐢𝐨𝐧
  A Vehicle Insurance can be detected by ML algorithm and avoid the losses of company
  Age 26 To 46, Sedan category car, which have maximum chances of fraud
 In sport and utility category of car having very less chance of fraud






![image](https://github.com/VIJAY84SH/Vehicle-Insurance-Fraud-Detection/assets/95535340/d1d41f23-6e25-4d98-8187-35fd5c7d1ee3)

Languages : Python, HTML, CSS
Platform : Jupyter Notebook, Visual Studio Code
Library Used : Numpy, Pandas, matplotlib, seaborn, Scikit-learn

