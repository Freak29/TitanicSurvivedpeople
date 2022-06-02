👋🛳️ Ahoy, welcome ! 
This is the legendary Titanic ML problem .The problem is simple: use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.
The sinking of the Titanic is one of the most infamous shipwrecks in history.


On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.
While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.In this dataset, we have to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).& save those predictions in a csv file we


We had two similar datasets here that include passenger information like name, age, gender, socio-economic class, etc. 
One dataset is titled `train.csv` and the other is titled `test.csv`.
* Train.csv will contain the details of a subset of the passengers on board (891 to be exact) and importantly, will reveal whether they survived or not, also known as the “ground truth”.
* Test.csv` dataset contains similar information but does not disclose the “ground truth” for each passenger. It’s your job to predict these outcomes.
Using the patterns we find in the train.csv data, we have to predict whether the other 418 passengers on board (found in test.csv) survived.
I have used various algorithms in the code to find out the most suitable one out of which light bgm algo gave maximum accuracy. I have used it to predict the outcome for test data and saved the predictions in the Submission.CSV file.