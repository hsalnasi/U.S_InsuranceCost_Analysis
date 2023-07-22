# U.S Insurance Cost Analysis 
A simple unguided analysis project was done as part of the Codecademy Data Foundations path. Access the notebook [Here](us-medical-insurance-costs.ipynb)
# Introduction 
Given a [*CSV file*](insurance.csv) as our dataset containing information about U.S medical insurance cost, The goal of the project is to extract new pieces of information and to see if the cost is related to a couple of factors `(Age - Sex - health status)`.  

# Approach  
packages used for this project :
#### Loading, and cleaning Data:
  - CSV
  - Pandas
#### Visualizing :
- matplotlib
- Seaborn

# EDA 
The Data was first loaded and put into a data frame using pandas and a couple of helper functions were built using python. Then, The data frame has been explored for some errors and missed values.
After handling errors, Some questions were raised about the Data 
- What is the Average Age in the Data set?
- How can the cost relate to Gender?
- is cost related to Age and health status?
- comparing The number of children each individual has.
- Detect bias if any in the Dataset.


  # *Findings* and conclusion
  Given a CSV file with medical insurance information. The data has been analyzed looking for relations between the cost and varies attributes `(Age- Sex - Health status [Smoker - noneSmoker])`.
  
  after analyzing the Data, the following has been conducted :
  The Smoker male will have to pay more for insurance compared to non-smokers. It is also noted that in general males tend to pay more for insurance than females according to the given data. 
  Same as males who smoke, Female smokers would have to pay a little more than double the price for insurance. In general, Non-smokers pay less in both genders. The older the more expensive the cost is 
  When it comes to age, the average age in the data was **39 years old** while the oldest patients were 64 years old, and the youngest was around 18 years old. 
  People with 3 children are also prone to pay more than other people in the dataset. 
  
  **, In conclusion,**, It was proven that indeed the cost of medical insurance is related to Age, Sex, Health Status. 
  






