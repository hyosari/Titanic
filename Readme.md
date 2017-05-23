# Titacinc: Machine Learning from Disaster
### Data Set Description 
On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. **Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.**

Source by: [Link](https://www.kaggle.com/c/titanic)
#### Data derectory 
<div>
The data has been split into two groups:
	•	training set (train.csv)
	•	test set (test.csv)
</div>
<div>
Variable		Definition

survival.     	Survival            0 = No , 1 =yes 
pclass.      	Ticket class.    1 = 1st, 2 = 2nd, 3 = 3rd 
sex.           	Sex 
Age.          	Age in years 
sibsp. 			Number of siblings / spouses aboard the Titanic 
parch        	Number of parents / children aboard the Titanic 
ticket.       		Ticket number
fare.          	Passenger fare 
cabin.       		Cabin number 
embarked. 	Port of Embarkation.          C = Cherbourg, Q = Queenstown, S = Southampton 

<div>
Detail : [Link](https://www.kaggle.com/c/titanic/data)            

### Objective 
Predict and analysis of what sorts of people were likely to survive.

### Prediction Acuraccy
<div>

Decision tree :  0.83
AdaBoast : 0.83
RandomForest : 0.83

SVM : 0.74
MLP : 0.82

</div>