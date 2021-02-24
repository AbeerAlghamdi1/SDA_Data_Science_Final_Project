# **Employee Turnover Prediction**


<p align="center">
  <img width="700" height="450" src="https://user-images.githubusercontent.com/75139815/109006730-6aa41700-76bc-11eb-8232-34e3280716e7.png">
</p>
  

### **Employee Turnover rate:**

Employee Turnover rate is the measurement of the total number of employees who leave an organization in a particular year. 
 Employee Turnover Prediction means to predict whether an employee is going to leave or not leave the organization in the 
coming period.


### **Objectives:**

1. Determine which factors have a high effect on employees turnover rate.
2. Create a model that can predict whether an employee will leave the company or not.


### **Exploratory Data Analysis (EDA):**

- The dataset has 14,999 employees observation and 10 Features.
- No variable column has null/missing values.
- Dataset has 3,008 duplicate values
- 83% of employees stayed and 17% of employees left the company.
- Employees who had a satisfaction rate 0.5 or less tend to leave the company more.
- The average monthly work hours of employees who left the company is more than that of the employees who stayed.
- Most of the employees had experiences between 2-4 years at the company.
- The employees who had workplace accidents are less likely to leave than that of the employee who did not have workplace accidents.
- Most of those left didn't get the promotion in the previous 5 years.
- The sales department is having the highest numbers of turned-over employees followed by technical and support.
- Employees with low to average salaries tend to leave the company.


<p align="center">
  <img width="550" height="450" src="https://user-images.githubusercontent.com/75139815/109011584-1d2aa880-76c2-11eb-9387-f80c8ef0448d.png">
</p>


### **Finding:**

I used correlation analysis to determine which factors contribute the most to employee turnover. So, I found that the most correlated was employee satisfaction which had a score of -0.35. A negative correlation means that the likelihood of departure increases as employee satisfaction decreases. And I discovered that the years spent at the company, the number of projects worked, and the employee's average monthly hours had the greatest impact on employee satisfaction.


<p align="center">
  <img width="600" height="450" src="https://user-images.githubusercontent.com/75139815/109011758-4f3c0a80-76c2-11eb-9f4f-08c4ada69cda.png">
</p>

### **Potential Solution**

- Allocate incentive budget to boost employee satisfaction and productivity.
- Provide overtime rewards (may not financial rewards) to those who work more than the ideal monthly average hours.
- The division of tasks must be clear and fair among all employees as we can.
- Make employees feel are appreciated and well-respected in the workplace environment.

### **Models used:**

I used 4 models to predict the Employee Turnover rate listed below:

- Baseline Model had a score of 83%.
- Logistic Regression had a score of 83%.
- KNeighbors Classifier had a score of  94%.
- Random Forest Classifier had a score of 98.03% before tuning, and 98.29% after tuning with GridSearchCV and RandomizedSearchCV.

#### **To Conclude:**

- The Random Forest Classifier model with GridSearchCV and RandomizedSearchCV hyperparameters got the highest accuracy scores in predicting the Employees Turnover Rate.

<p align="center">
  <img width="650" height="450" src="https://user-images.githubusercontent.com/75139815/109011612-24ea4d00-76c2-11eb-8c1a-9381440ab638.png">
</p>



### **Summary**

Employee turnover analysis is not going to provide a list of employees who the model predicts are likely to quit. This is not the objective of this analysis. Because we can’t have an algorithm for everyone. Employee turnover analysis can help guide decisions, but not make them. We can use these analytics in conjunction with employee feedback, to make the best decisions possible.
<p></p>
 Here you can find my [code](https://github.com/AbeerAlghamdi1/SDA_Data_Science_Final_Project/tree/main/Code) ,and dataset that was used.

