# **High Mortgage Rates**
## *Project #01, Group 12* 

### **Project Description:**
Are cannabis laws affecting housing prices in the U.S.?

What is the correlation between recreational cannabis sales and home valuations in legalized vs. non-legalized states?

### **HYPOTHESIS:**
Housing prices increase at a greater rate when recreational cannabis sales are legalized. 

Research Questions:

1. How do housing prices compare between legal and non-legal states with similar HPI before legalization?
	
	A. Narrowing it to 3-5 states, look at recreational cannabis sales.
2. Choose the First Three States in the Continental U.S. to Legalize Recreational Cannabis and compare HPI.    			
	
	A. We Chose Colorado, Washington, and Oregon and compared these to non-legal control states:
            
		i. Colorado-Vermont
					
	![colorado_vermont](https://user-images.githubusercontent.com/112498067/200094494-eaa72f41-34a8-4a2d-9d72-a51b735f8088.png)
	
		ii. Washington - New Jersey	
					
	![washington_jersey](https://user-images.githubusercontent.com/112498067/199375200-9e4fe315-f62d-4137-aef9-d0e5ca04f34f.png)
	
        iii. Oregon - Rhode Island
					
	![oregon_rhode](https://user-images.githubusercontent.com/112498067/199375257-b495f0df-178b-492d-9482-7dee846c27bd.png)	
	
3. How is the annual change statistically different from the states we looked at before?

	A. Create line graphs of the percent change in HPI for legal versus non-legal states:
	
	![annual_change](https://user-images.githubusercontent.com/112498067/199375350-96509060-af0b-4723-86ca-5e309da04c1f.png)
	
	B. Create scatter plots of legal versus non-legal populations and analyze the data statistically:
	
	![legal_annual_change](https://user-images.githubusercontent.com/112498067/199375432-0d7d6f5f-ce82-4867-9a70-a8494b4eb4d8.png)
	
	![nonlegal_annual_change](https://user-images.githubusercontent.com/112498067/199375498-11488a2c-3160-4bf3-8c79-96c19662ef7f.png)
	
	C. Perform a Box and Whiskers analysis of the percent change in HPI for legal and non-legal states.	
	
	![boxplot](https://user-images.githubusercontent.com/112498067/199375564-00fb8eb7-2cbf-4307-848f-00d2806a36f4.png)	
	
	D. Perform a T-Test of combined results:
	
		Ttest_indResult(statistic=3.516179600926685, pvalue=0.001343851096754382)			
		
# **CONCLUSION**

We graphed the legal and non-legal data separately with scatter plots and created regression lines to determine the slopes of the two separate populations for comparison. In our final Box-and-Whisker graph, we directly compared the two data sets of legal and non-legal 'State Buds' and performed a T-Test, assuming that we can extrapolate that our sample data are independent, approximately normally distributed, and have a similar variance between our two groups (i.e., legal and non-legal). The resulting p-value was 0.00134385, lower than 0.05 (the generally accepted threshold). As a result, we reject the null hypothesis and are confident the results strongly suggest that recreational cannabis sales have a direct impact on the rate of increase in housing prices.

### **Credits**
Bogin, Alexander N., Doerner, William M. and Larson, William D. (2019). "Local House Price Dynamics: New Indices and Stylized Facts". Real Estate Economics, volume 47, issue 2, pages 365-398. The initial FHFA WP 16-01 is accessible at http://www.fhfa.gov/papers/wp1601.aspx.
