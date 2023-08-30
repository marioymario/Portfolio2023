## User Churn Project | Preliminary Data Summary
Prepared for: Waze Leadership Team

#### Overview

The Waze data team is currently developing a data analytics project aimed at increasing overall growth by preventing monthly user churn on the Waze app. For the purposes of this project, churn quantifies the number of users who have uninstalled the Waze app or stopped using the app. 

This report offers a preliminary data summary, information on the project status and key insights of Milestone 2, which impact the future development of the overall project. 

#### Project Status

Milestone 2 - Compile Summary Information 

**Target Goal**: Inspect user data to learn important relationships between variables. 

🎯 Methods: 
Built a dataframe
Each row represents a single observation, and each column represents a single variable
Collected preliminary statistics
Analyzed user behavior

🎯 Impact: Our team determined important relationships between variables that will guide further analysis of user data. 

#### Key Insights

- The dataset contains 82% retained users and 18% churned users.
- The dataset contains 12 unique variables with types including objects, floats, and integers; the label column is missing 700 values with no indication that the omissions are non-random.
- Churned users averaged ~3 more drives in the last month than retained users.
- Retained users used the app on over twice as many days as churned users in the last month.
- The median churned user drove ~200 more kilometers and 2.5 more hours during the last month than the median retained user.
- Churned users had more drives in fewer days, and their trips were farther and longer in duration. Perhaps this is suggestive of a user profile; our team will have to continue exploring! 
- The median user who churned drove 608 kilometers each day they drove last month, which is almost 250% the per-drive-day distance of retained users.
- Regardless of user churn, the users represented in this data drive a lot! It is probably safe to assume that this data does not represent typical drivers at large. 


#### Next Steps

Our team recommends gathering more data on the super-drivers. It's possible that the reason they’re driving so much is also the reason why the Waze app does not meet their specific set of needs, which may differ from the typical driver.
The immediate next step is to conduct thorough EDA and develop data visualizations to illustrate the narrative behind the data and guide future project decisions. 