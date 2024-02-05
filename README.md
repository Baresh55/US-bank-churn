1.	WHAT IS THE DISTRIBUTION OF CUSTOMERS ACROSS DIFFERENT GEOGRAPHIES AND GENDERS? 

I included the gender and geography columns within the SELECT statement and utilized the COUNT function to determine the quantity of bank customers. Additionally, I applied the GROUP BY function to categorize them based on Geography and concluded by employing the ORDER BY function to arrange the customer count results in descending order.


2.	WHAT IS THE NUMBER OF ACTIVE MEMBERS, AND HOW DOES IT CORRELATE WITH TENURE? 

Within the SELECT statement, I included the tenure column and utilized the COUNT function to ascertain the quantity of active clients. Subsequently, I applied the WHERE function to differentiate between active and non-active clients. Following this, I employed the GROUP BY clause based on tenure and concluded by implementing the ORDER BY function to arrange the active clients in descending order. 


3.	WHAT IS THE RELATIONSHIP BETWEEN CREDIT SCORE AND CUSTOMER CHURN? 

Within the SELECT statement, I included the "exited" column and computed the average credit score by utilizing the AVG function. Subsequently, I categorized the results based on whether clients had exited, using the GROUP BY function. 


4.	WHAT IS THE CORRELATION BETWEEN AVERAGE ESTIMATED SALARY AND NUMBER OF PRODUCTS? 

In the SELECT statement, I included the "number of products" column and calculated the average estimated salary using the AVG function. Additionally, I applied the WHERE statement to filter products within the range of 1 to 4. Finally, I grouped the average estimated salary based on the number of products. 


5.	HOW DOES AVERAGE TENURE COMPARE TO AVERAGE AGE IN THE DIFFERENT GEOGRAPHIES? 

In the SELECT statement, I chose the relevant columns, specifically geography followed by average tenure and average age which I computed using the AVG function. Subsequently, I grouped the results by geography and ordered them in descending order based on tenure. Finally, I imposed a limit to restrict the output to the top 10 results. 


6.	HOW DOES AVERAGE TENURE VARY ACROSS THE DIFFERENT AGES? 

Within the select statement of the query, I included age and average tenure which I calculated using the AVG function. I further grouped by age in order to categorize the average tenure by age. 


7.	HOW DOES GENDER COMPARE TO CREDIT SCORE AND CUSTOMER CHURN? 

In the query's SELECT statement, I included gender along with the average credit score, computed using the AVG function, and the customer churn, determined by summing the exited values. Ultimately, I grouped the results by gender to organize the average credit score and customer churn based on gender.




