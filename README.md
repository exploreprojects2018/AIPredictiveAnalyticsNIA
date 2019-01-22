# AIPredictiveAnalyticsNIA
Collections Regular payment of customer loan dues pay a very important attribute in financial industry. When the customers do not pay their loan dues in time there is lot of overhead which gets involved in the organization to ensure payment from the customer and ensuring that it does not turn into NPA. Hence, it is important to identify the pattern establishing a prediction for the customers who turn ‘bad’ in the future.  Your challenge is to identify and develop solutions for customers who are ‘good’ today and paying their EMI’s on time but may turn into ‘bad’ in future so that organization can take timely corrective actions.
# Project description:
Challenge for Collections: Idea is to identify and develop solutions for customers who are ‘good’ today and paying their EMI’s on time but may turn into ‘bad’ in future so that organization can take timely corrective actions. Solution: Advanced analytics techniques that use both historical and new data to forecast activity, current market trends and behavior is Predictive Analytics. 
# Idea AI Predictive Analytics:
# Fraud Detection :
Using predictive analytics, banks can define fraud prediction models based on past cases of fraud and on cases deemed suspect. Predictive analytics searches for patterns and trends in data to determine why something is happening. Validation screening Predictive analytics can be used to process huge volumes of applications, without excluding important variables, and without delays or errors. Using Artificial intelligence and machine learning , Advanced analytics tool identify the prediction of future errors in borrowers and detects using algorithm to screen validate the customers and finds solution to prevent them in future. The trained model has got trained with 5 lac records, will work on loan behaviors prediction using machine learning models. Data Mining is a promising area of data analysis which aims to extract useful knowledge from tremendous amount of complex data sets. This work aims to develop a model and construct a prototype for the same using a data set available. The model is a decision tree based classification model that decides the decision. Prior to building the model, the dataset is pre-processed, reduced and made ready to provide efficient predictions. The final model is used for prediction with the test dataset and the experimental results prove the efficiency of the built model. 
<h>https://gallery.azure.ai/Experiment/Online-Fraud-Detection-Step-1-of-5-Generate-tagged-data-14</h>

# Risk Analysis & Profit Analysis:
# Analysis Scenario
A loan manager is requesting a statistical model to help her department determine which loan applicants are creditable, i.e. most likely to repay their loans. An applicant’s demographic and socio-economic profiles are considered by loan managers before a decision is made regarding his/her loan application. The manager’s goal is to minimize risk and maximize profits for the bank’s loan portfolio. The manager shares the information that for the type of loans the model would predict, if the borrower pays back the loan, the bank makes a profit of 35% the value of the loan. On the other hand, if the borrower defaults, the bank’s loss is 100%. The bank does not lose money for applicants who are rejected and the manager claims the model does not have to take into account the opportunity cost for applicants who would have repaid the loan but were rejected.
Upon receiving this request, I decided to develop a model for the manager that maximizes a profit-cost function given the provided data. The priority of the model fitting task will be prediction in this case as the manager has not specifically requested an interpretable model, but has requested a model with the best profit characteristics.
Dataset: <h>https://archive.ics.uci.edu/ml/datasets/bank+marketing#</h>

Bank FAQ in chatbot helps to get knowledge immediately for account opening, bank documents preparation..
https://bot.dialogflow.com/ca792c2f-2a66-4b99-bebf-348cc39ced9a

Few questions for discussions
1)"What are the documents required for opening a Current Account of a sole proprietorship firm",
"Following documents are required to open a Current Account of a sole proprietorship entity: Proof of existence in the name of firm Proof of address in the name of firm KYC of the proprietor Any two of the below listed documents shall be obtained for establishing proof of existence. Registration certificate/license issued by Municipal authorities such as Shop & Establishment Certificate/Trade License CST/VAT/Service Tax Certificate or Letter Of Registration for CST/VAT/Service Tax Certificate/Registration document issued by Professional Tax authorities Valid Business License or Certificate Of Registration issued by State/Central Government authority (validity would include the grace period for renewal as mentioned in the certificate) RBI/SEBI Registration Certificate License issued by Food and Drug Control Authorities Import - Export certificate (IEC Code) issued by the Director General of Foreign Trade Documents for establishing proof of address Landline telephone bill/electricity bill of public & approved private operators in the state. (Bills not to be older than 4 months from the date of account opening) Property Ownership Deed i.e. title deeds of the property in the name of the firm duly stamped and registered TAN Allotment Letter issued in the name of the firm Latest property tax or water tax paid receipt/bill raised in the name of the firm Existing bank account statement or passbook of a PSU/private sector/foreign bank. Statement not older than 4 months from the date of account opening to be accepted ** This is only indicative list. Please visit your nearest branch for details View more"],
2)Can I transfer my Current Account from one branch to another?
"Yes, Current Accounts can be transferred from one branch to another. However, there are certain restrictions. Please visit your nearest branch for details.


Predicting loan defaults with decision trees.

Dataset: UCI-credit card defaults
Datasource: https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients
UseCase: Banks loses quite billion of money by default payments in credit cards. 

Solution
A decision tree classifier is trained using 30,000 credit card holder data from Taiwan. Using the predictive model, possibly defaulting clients are identified at an accuracy of 82.1%. Moreover, repayment status and amount of previous payments are identified as dominating decision factors for default classification.
Utilizing machine learning on client data records like this, banks and other financing institutions can have a better grasp of people’s capacity to pay up their debts and loans; thus, allowing them to make better data-driven decisions.
We have also created a interactive voice to message Chatbot, ‘CreditCardExpert’, gives probability of default score to banks for determining credit default in interactive UI.
url: https://bot.api.ai/a5a29ae3-77b6-42b5-85f8-ad39650116cd

AI Technology and Libraries
•	General AI Platforms - Google.
•	Virtual Agents - Google, api.ai
•	Open Source –numpy,panda,scikit, spyder ide, anaconda package-python.
Algorithms:
•	KNN(K-Nearest Neighbor)
•	ANN(Artificial Neural Network)
•	LinearRegressor algorithm
•	DD3(DecisionTree Algorithm)
Consoles:
•	Ipython-console 



Screenshots:
DataAnalysis(Future Analysis)
 
Artificial Neural Network Model(Learning Model):
 
Decision tree
#                          levelName    n Avg Limit % Good Credit % Default
## 1  All                               NA                      NA        NA
## 2   ¦--20-29                         NA                      NA        NA
## 3   ¦   ¦--Female                    NA                      NA        NA
## 4   ¦   ¦   ¦--Married               NA                      NA        NA
## 5   ¦   ¦   ¦   ¦--High School      192  $ 99,688          0.21      0.29
## 6   ¦   ¦   ¦   ¦--University       814  $118,206          0.25      0.28
## 7   ¦   ¦   ¦   °--Graduate School  148  $176,689          0.45      0.16
## 8   ¦   ¦   °--Single                NA                      NA        NA
## 9   ¦   ¦       ¦--High School      365  $110,219          0.31      0.24
## 10  ¦   ¦       ¦--University      2337  $119,718          0.28      0.24
## 11  ¦   ¦       °--Graduate School 2363  $150,165          0.45      0.19
## 12  ¦   °--Male                      NA                      NA        NA
## 13  ¦       ¦--Married               NA                      NA        NA
## 14  ¦       ¦   ¦--High School       53  $103,962          0.23      0.32
## 15  ¦       ¦   ¦--University       197  $110,457          0.25      0.26
## 16  ¦       ¦   °--Graduate School   45  $161,556          0.36      0.27
## 17  ¦       °--Single                NA                      NA        NA
## 18  ¦           ¦--High School      325  $ 70,062          0.22      0.30
## 19  ¦           ¦--University      1462  $ 91,826          0.20      0.27
## 20  ¦           °--Graduate School 1134  $144,180          0.41      0.19
## 21  ¦--30-39                         NA                      NA        NA
## 22  ¦   ¦--Female                    NA                      NA        NA
## 23  ¦   ¦   ¦--Married               NA                      NA        NA
## 24  ¦   ¦   ¦   ¦--High School      500  $141,260          0.34      0.22
## 25  ¦   ¦   ¦   ¦--University      1948  $173,850          0.40      0.21
## 26  ¦   ¦   ¦   °--Graduate School 1062  $246,365          0.67      0.19
## 27  ¦   ¦   °--Single                NA                      NA        NA
## 28  ¦   ¦       ¦--High School      266  $185,677          0.49      0.16
## 29  ¦   ¦       ¦--University      1220  $192,311          0.39      0.18
## 30  ¦   ¦       °--Graduate School 1505  $242,930          0.65      0.16
## 31  ¦   °--Male                      NA                      NA        NA
## 32  ¦       ¦--Married               NA                      NA        NA
## 33  ¦       ¦   ¦--High School      271  $150,701          0.30      0.31
## 34  ¦       ¦   ¦--University      1010  $170,178          0.34      0.26
## 35  ¦       ¦   °--Graduate School  635  $257,008          0.59      0.22
## 36  ¦       °--Single                NA                      NA        NA
## 37  ¦           ¦--High School      279  $136,022          0.26      0.24
## 38  ¦           ¦--University      1045  $142,737          0.27      0.23
## 39  ¦           °--Graduate School 1240  $229,266          0.49      0.19
## 40  ¦--40-49                         NA                      NA        NA
## 41  ¦   ¦--Female                    NA                      NA        NA
## 42  ¦   ¦   ¦--Married               NA                      NA        NA
## 43  ¦   ¦   ¦   ¦--High School      688  $133,808          0.38      0.26
## 44  ¦   ¦   ¦   ¦--University      1331  $176,255          0.45      0.22
## 45  ¦   ¦   ¦   °--Graduate School  626  $255,719          0.67      0.18
## 46  ¦   ¦   °--Single                NA                      NA        NA
## 47  ¦   ¦       ¦--High School      235  $139,617          0.34      0.25
## 48  ¦   ¦       ¦--University       407  $167,052          0.35      0.20
## 49  ¦   ¦       °--Graduate School  247  $254,211          0.60      0.20
## 50  ¦   °--Male                      NA                      NA        NA
## 51  ¦       ¦--Married               NA                      NA        NA
## 52  ¦       ¦   ¦--High School      414  $137,222          0.29      0.27
## 53  ¦       ¦   ¦--University       824  $165,534          0.32      0.27
## 54  ¦       ¦   °--Graduate School  693  $266,869          0.59      0.23
## 55  ¦       °--Single                NA                      NA        NA
## 56  ¦           ¦--High School      197  $100,902          0.21      0.24
## 57  ¦           ¦--University       334  $110,329          0.18      0.27
## 58  ¦           °--Graduate School  201  $235,323          0.41      0.20
## 59  ¦--50-59                         NA                      NA        NA
## 60  ¦   ¦--Female                    NA                      NA        NA
## 61  ¦   ¦   ¦--Married               NA                      NA        NA
## 62  ¦   ¦   ¦   ¦--High School      369  $119,837          0.32      0.25
## 63  ¦   ¦   ¦   ¦--University       339  $168,112          0.36      0.27
## 64  ¦   ¦   ¦   °--Graduate School  172  $257,035          0.73      0.19
## 65  ¦   ¦   °--Single                NA                      NA        NA
## 66  ¦   ¦       ¦--High School      133  $103,684          0.27      0.21
## 67  ¦   ¦       ¦--University       112  $145,714          0.34      0.17
## 68  ¦   ¦       °--Graduate School   56  $232,857          0.59      0.18
## 69  ¦   °--Male                      NA                      NA        NA
## 70  ¦       ¦--Married               NA                      NA        NA
## 71  ¦       ¦   ¦--High School      267  $136,180          0.32      0.31
## 72  ¦       ¦   ¦--University       294  $157,619          0.27      0.29
## 73  ¦       ¦   °--Graduate School  260  $276,192          0.52      0.25
## 74  ¦       °--Single                NA                      NA        NA
## 75  ¦           ¦--High School       81  $ 95,926          0.20      0.20
## 76  ¦           ¦--University        86  $ 90,930          0.16      0.24
## 77  ¦           °--Graduate School   53  $180,755          0.32      0.19
## 78  °--60-69                         NA                      NA        NA
## 79      ¦--Female                    NA                      NA        NA
## 80      ¦   ¦--Married               NA                      NA        NA
## 81      ¦   ¦   ¦--High School       56  $124,464          0.30      0.25
## 82      ¦   ¦   ¦--University        38  $184,211          0.50      0.29
## 83      ¦   ¦   °--Graduate School   24  $267,083          0.71      0.33
## 84      ¦   °--Single                NA                      NA        NA
## 85      ¦       °--High School       15  $ 86,000          0.20      0.40
## 86      °--Male                      NA                      NA        NA
## 87          ¦--Married               NA                      NA        NA
## 88          ¦   ¦--High School       40  $173,000          0.22      0.22
## 89          ¦   ¦--University        42  $173,095          0.50      0.45
## 90          ¦   °--Graduate School   50  $288,600          0.56      0.24
## 91          °--Single                NA                      NA        NA
## 92              ¦--High School       12  $149,167          0.33      0.17
## 93              °--University        13  $192,308          0.15      0.08
Result:
 

ChatBot: CreditCard Defaulters

 


The tool helps the banks to minimize the possible losses and can increase the volume of credits. The result of this credit risk assessment will be the prediction of Probability of Default (PD) of an applicant. Hence, it becomes important to build a model that will consider the various aspects of the applicant and produces an assessment of the Probability of Default of the applicant. This parameter PD, help the bank to make decision if they can extend to offer the loan services to the applicant or not. In such scenario the data being analyzed is huge and complex and using data mining techniques to obtain the result is the most suitable option provided its efficient analytical methodology that finds useful knowledge. There are many such work has been done previously, but they have not explored the use of the features in machine learning classifier. Decision Trees Along with linear classifiers, decision trees are amongst the most widely used classification techniques in the real world. This method is extremely intuitive, simple to implement and provides interpretable predictions. Classifier is designs a simple, recursive greedy algorithm to learn decision trees from data. Finally, you will extend this approach to deal with continuous inputs, a fundamental requirement for practical problems. In this module, you will investigate a brand new case-study in the financial sector: predicting the risk associated with a bank loan. You will implement your own decision tree learning algorithm on real loan data. 
Steps: Data Exploration and Preprocessing Feature Engineering Model Validation and Selection Model Evaluation Conclusion and Discussion
https://youtu.be/JSfzwGIPSUk
