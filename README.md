# **High Mortgage Rates**
## *Project #01, Group 12* 


### **Project Description:**
Are cannabis laws affecting housing prices in the U.S.?

What is the correlation between recreational cannabis sales and home valuations in legalized vs. non-legalized states?


### **HYPOTHESIS:**
If a state has legalized recreational cannabis, then it’s expected to have an accelerated increase in their house prices. 


Research Questions:

1. How do housing prices compare between legal and non-legal states with similar HPI before legalization?
    
		A. Narrowing it to 3-5 states, look at recreational cannabis sales.
		
2. Choose the First Three States in the Continental U.S. to Legalize Recreational Cannabis and compare HPI.    
				
		A. We Chose Colorado, Washington, and Oregon and compared these to non-legal control states:
            
				i. Colorado-Vermont
	![colorado_vermont](https://user-images.githubusercontent.com/112498067/198892000-9e729b6e-732f-4bf1-9645-4e1f9fc543ef.png)

							
				ii. Washington - New Jersey
	![washington_jersey](https://user-images.githubusercontent.com/112498067/198892013-8be11c28-bb5f-459a-9cdc-1a1ea136cd18.png)

            
				iii. Oregon - Rhode Island
	![oregon_rhode](https://user-images.githubusercontent.com/112498067/198892028-38a5d08f-2fc4-4785-88ce-792e37d87309.png)

				
				
3. How is the annual change statistically different from the states we looked at before?
		
		A. Create line graphs of the percent change in HPI for legal versus non-legal states:
	![annual_change](https://user-images.githubusercontent.com/112498067/198892156-edcaf236-7465-4b42-98a3-c14bebec4fe7.png)

		B. Create scatter plots of legal versus non-legal populations and analyze the data statistically:
		
	![legal_annual_change](https://user-images.githubusercontent.com/112498067/198892084-bf535827-48c4-4cc0-8388-f8b05e2d3afd.png)
	![nonlegal_annual_change](https://user-images.githubusercontent.com/112498067/198892095-5ead76e6-f567-437d-9a5b-85da59a7c4c7.png)

		
		C. Perform a Box and Whiskers analysis of the percent change in HPI for legal and non-legal states.
	![boxplot](https://user-images.githubusercontent.com/112498067/198892243-b3e69dd3-4c94-43bd-9761-9a82d3594520.png)

				
				
		D. Perform a T-Test of combined results:
				
		Ttest_indResult(statistic=3.516179600926685, pvalue=0.001343851096754382)			
		
# **CONCLUSION**

In our final box and whisker graph, we directly compared the two data sets of legal and non-legal 'State Buds' and performed a T-Test. The resulting p-value of 0.00134385 < 0.05 (The generally accepted threshold). As a result, we failed to reject the null hypothesis and are confident that the results unequivocally prove that recreational cannabis sales have a direct impact on the rate of increase in housing prices.
