# Employee Satisfaction Sailford Motors.
---

### **Overview:**

This folder includes the data and code to analyze a dataset and build predictive models that can provide insights to the Human Resources (HR) department of a large consulting firm.

### **Problem:**

It is time-consuming and expensive to find, interview, and hire new employees, increasing employee retention will be beneficial to Salifort Motors.

The HR department at **Salifort Motors** wants to take some initiatives to improve **employee satisfaction** levels at the company. 
They collected data from employees. Looking to provide data-driven suggestions based on your understanding of the data.

- What’s likely to make the employee leave the company?

If we can predict employees likely to quit, it might be possible to identify the **factors** that contribute to their leaving. 

### **Solution:**

The models and the feature importances extracted from the models confirm that employees at the company are overworked. 

To retain employees, the following recommendations could be presented to the stakeholders:

* Cap the number of projects that employees can work on.
* Consider promoting employees who have been with the company for atleast four years, or conduct further investigation about why four-year tenured employees are so dissatisfied. 
* Either reward employees for working longer hours, or don't require them to do so. 
* If employees aren't familiar with the company's overtime pay policies, inform them about this. If the expectations around workload and time off aren't explicit, make them clear. 
* Hold company-wide and within-team discussions to understand and address the company work culture, across the board and in specific contexts. 
* High evaluation scores should not be reserved for employees who work 200+ hours per month. Consider a proportionate scale for rewarding employees who contribute more/put in more effort. 

**Next Steps**

It may be justified to still have some concern about data leakage. It could be prudent to consider how predictions change when `last_evaluation` is removed from the data. It's possible that evaluations aren't performed very frequently, in which case it would be useful to be able to predict employee retention without this feature. It's also possible that the evaluation score determines whether an employee leaves or stays, in which case it could be useful to pivot and try to predict performance score. The same could be said for satisfaction score. 

