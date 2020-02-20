Logistic Regression on Titanic Dataset

In this project I'm attempting to do data analysis on the Titanic Dataset. In the first step I'm doing a very quick data exploration and preprocessing on a visual level, Then I've done some data cleaning and built a Classifier that can predict whether a passenger survived or not.

Tools and Packages
In this project I've used the following tools and Python packages:
•	Jupyter Notebooks: This is the software that lets us run Python code in the browser and intermix markdown with cells containing code.
•	Numpy: This is pythons main scientific computing library. Its important for Data Science as all libraries in PyData Ecosystem rely on NumPy as one of their main building blocks
•	Pandas: This is the data analysis tool of choice in Python. It allows fast analysis and data cleaning and preparation using powerful data structures like dataframes and series.
•	Scikit-learn: The machine learning package of Python. Makes implementing ML Algorithms extremely simple.

Dataset Description:
•	Survived: Survived (1) or died (0)
•	Pclass: Passenger’s class
•	Name: Passenger’s name
•	Sex: Passenger’s sex
•	Age: Passenger’s age
•	SibSp: Number of siblings/spouses aboard
•	Parch: Number of parents/children aboard
•	Ticket: Ticket number
•	Fare: Fare
•	Cabin: Cabin
•	Embarked: Port of embarkation. C- Cherbourg, S – Southampton, Q - Queenstown


Results
The classifier built here has a prediction score of 0.81, i.e., we get an average accuracy of 80+%. This is a pretty good accuracy for starters and could be improved upon by coming up with newer, better features by using some feature engineering. This is something I could work on in the future.
