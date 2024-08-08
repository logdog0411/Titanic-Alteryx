# Titanic-Alteryx
I FINALLY try the Titanic competition... with only Alteryx tools. 

Day 1 (240807): Rough Swag. I used the easiest tool available, the Machine Learning Assisted Modeling tool. 
Got a .77272 accuracy, good for position #9929 out of 16,162. 

On the Train set, I removed the null rows from the Embarked field prior to building the model
I replaced null values for Age with the Mean

On the test set, I replaced nulls with the mean, same with the fare field. 
Assisted Modeling gave me an XGBoost model, which graded out at a 82.6% accuracy in the build phase
I may tweak some null value treatments to see if I can upgrade the model. 
