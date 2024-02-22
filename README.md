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
The amount of claims in different months does not differ so much that we can find out a special point from it
Top 5 Make of claims in order is:

1.Pontiac (Highest)
2.Toyota
3.Honda
4.Mazda
5.Chevrole

Most accidents occur in Urban areas and the remaining occur in Rural areas.
![Accident area](https://github.com/VIJAY84SH/Vehicle-Insurance-Fraud-Detection/assets/95535340/473598ac-0c66-4e2e-8f96-24a535897ff7)

Sedan vehicle categories has more chancea of fraud 
![image](https://github.com/VIJAY84SH/Vehicle-Insurance-Fraud-Detection/assets/95535340/bf56c7ba-036e-4d8d-8aab-963b5a31f9be)

Most of the frauds are in age of 26 to 45
![image](https://github.com/VIJAY84SH/Vehicle-Insurance-Fraud-Detection/assets/95535340/f0f979c4-7649-459e-aff1-d4a54b617d32)



# 𝐂𝐋𝐀𝐒𝐒 𝐈𝐌𝐁𝐀𝐋𝐀𝐍𝐂𝐄
![image](https://github.com/VIJAY84SH/Vehicle-Insurance-Fraud-Detection/assets/95535340/505300c1-a864-4e1f-bd22-a1d17990ce9c)

 Handling Class Imbalance using SMOTE
SMOTE is a popular technique used in machine learning to address class imbalance by generating synthetic samples for the minority class.
It works by creating synthetic instances of the minority class by interpolating between existing minority class instances.
This method helps in balancing the class distribution, making the dataset more suitable for training models.

# 𝐌𝐨𝐝𝐞𝐥 𝐑𝐞𝐬𝐮𝐥𝐭𝐬
![image](https://github.com/VIJAY84SH/Vehicle-Insurance-Fraud-Detection/assets/95535340/cbd2319c-69a9-493a-9f8e-04f03aafda45)


# 𝐀𝐝𝐯𝐚𝐧𝐭𝐚𝐠𝐞𝐬:
 1. Insurance company no need to assign specialists
 2. Save cost and time 
 3. Reduce financial burden of fraudulent claims

 # 𝐃𝐢𝐬𝐚𝐝𝐯𝐚𝐧𝐭𝐚𝐠𝐞:
 Recall score for class1 is less so some claim can not be detected

 # 𝐂𝐨𝐧𝐜𝐥𝐮𝐬𝐢𝐨𝐧
In conclusion, a machine learning algorithm can effectively identify potential cases of insurance fraud, particularly among sedan category cars with owners aged between 26 to 46, which exhibit higher susceptibility to fraudulent activities. Conversely, vehicles categorized as sports and utility vehicles demonstrate significantly lower probabilities of being associated with fraudulent claims

Languages : Python, HTML, CSS

Platform : Jupyter Notebook, Visual Studio Code

Library Used : Numpy, Pandas, matplotlib, seaborn, Scikit-learn

