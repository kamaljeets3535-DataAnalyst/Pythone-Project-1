# Pythone-Project-1
The purpose of this project is to master the exploratory data analysis (EDA) in banking with Pandas framework.

Input features (column names):

age - client's age in years (numeric)
job - type of job (categorical: admin., blue-collar, entrepreneur, housemaid, management, retired, self-employed, services, student, technician, unemployed, unknown)
marital - marital status (categorical: divorced, married, single, unknown)
education - client's education (categorical: basic.4y, basic.6y, basic.9y, high.school, illiterate, professional.course, university.degree, unknown)
default - has credit in default? (categorical: no, yes, unknown)
housing - has housing loan? (categorical: no, yes, unknown)
loan - has personal loan? (categorical: no, yes, unknown)
contact - contact communication type (categorical: cellular, telephone)
month - last contact month of the year (categorical: jan, feb, mar, ..., nov, dec)
day_of_week - last contact day of the week (categorical: mon, tue, wed, thu, fri)
duration - last contact duration, in seconds (numeric).
campaign - number of contacts performed and for this client during this campaign (numeric, includes the last contact)
pdays - number of days that have passed after the client was last contacted from the previous campaign (numeric; 999 means the client has not been previously contacted)
previous - number of contacts performed for this client before this campaign (numeric)
poutcome - outcome of the previous marketing campaign (categorical: failure, nonexistent, success)
emp.var.rate - employment variation rate, quarterly indicator (numeric)
cons.price.idx - consumer price index, monthly indicator (numeric)
cons.conf.idx - consumer confidence index, monthly indicator (numeric)
euribor3m - euribor 3 month rate, daily indicator (numeric)
nr.employed - number of employees, quarterly indicator (numeric)
Output feature (desired target):

y - has the client subscribed a term deposit? (binary: yes,no)
