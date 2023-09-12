# Consumer-Churn

## Objectives:
- Finding the % of Churn Customers and customers that keep in with the active services.
- Analysing the data in terms of various features responsible for customer Churn
- Finding a most suited machine learning model for correct classification of Churn and non churn customers.

## Dataset:
 [Telco Customer Churn](https://www.kaggle.com/bhartiprasad17/customer-churn-prediction/data)
 
### The data set includes information about:
- Customers who left within the last month – the column is called Churn
- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents

## Implementation:
**Libraries:** sklearn, Matplotlib, pandas, plotly, and NumPy
**Auto ML Libraries:** Pycaret, Pandas Profiling

## Few glimpses of EDA:
### 1. Churn distribution:
> ![Churn distribution](https://github.com/ashwin044/Consumer-Churn/blob/main/Output/churn%20percentage.png)<br>
> 26.6 % of customers switched to another firm.

### 2. Churn distribution with respect to gender:
> ![Churn distribution wrt Gender](https://github.com/ashwin044/Consumer-Churn/blob/main/Output/Churn%20Distribution%20w.r.t%20Gender%20Male(M)%2C%20Female(F).png)<br>
> There is negligible difference in customer percentage/count who chnaged the service provider. Both genders behaved in similar fashion when it comes to migrating to another service provider/firm.`

### 3. Customer Contract distribution:
> ![Customer contract distribution](https://github.com/ashwin044/Consumer-Churn/blob/main/Output/Customer%20contract%20distribution.png)<br>
> About 75% of customer with Month-to-Month Contract opted to move out as compared to 13% of customrs with One Year Contract and 3% with Two Year Contract

### 4. Payment Methods:
> ![Distribution of Payments methods](https://github.com/ashwin044/Consumer-Churn/blob/main/Output/Customer%20Payment%20Method%20distribution%20w.r.t.%20Churn.png) ![Churn wrt payment methods](https://github.com/ashwin044/Consumer-Churn/blob/main/Output/Customer%20Payment%20Method%20distribution%20w.r.t.%20Churn_1.png)<br>
> Major customers who moved out were having Electronic Check as Payment Method.
> Customers who opted for Credit-Card automatic transfer or Bank Automatic Transfer and Mailed Check as Payment Method were less likely to move out.

### 5. Internet services:
> Several customers choose the Fiber optic service and it's also evident that the customers who use Fiber optic have high churn rate, this might suggest a dissatisfaction with this type of internet service.
> Customers having DSL service are majority in number and have less churn rate compared to Fibre optic service.<br>
![Churn distribution w.r.t Internet services and Gender](https://github.com/ashwin044/Consumer-Churn/blob/main/Output/Churn%20w.r.t%20Internet%20Service%20Type.png)

### 6. Online Security:
> As shown in following graph, most customers churn due to lack of online security<br>
![Churn distribution w.r.t online security](https://github.com/ashwin044/Consumer-Churn/blob/main/Output/Churn%20w.r.t%20Online%20Security.png)

### 7. Paperless Billing:
> Customers with Paperless Billing are most likely to churn.<br>
![Churn distribution w.r.t mode of billing](https://github.com/Pradnya1208/Telecom-Customer-Churn-prediction/blob/main/output/billing.PNG?raw=true)

### 8. Distribution w.r.t Tenure:
> ![Tenure](https://github.com/ashwin044/Consumer-Churn/blob/main/Output/Tenure%20vs%20Churn.png)<br>
> New customers are more likely to churn.
