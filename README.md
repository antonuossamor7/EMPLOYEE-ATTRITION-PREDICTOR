# Can Employee Attrition be Predicted?

## Website:   https://emily-keymon.github.io/Final-Project/

### Tableau:  https://public.tableau.com/profile/antonuos.samor#!/vizhome/EMPLOYEE_ATTRITION_PREDICTOR/Story1

Our project is based around a fictional dataset that gave us various details on employees and whether they attrited or not. The challenge was to incorporate machine learning to give as an algorithm, for a company or manager to use, that determines if an employee will leave their position. Unfortunately, this data does not allow the creation of a model that can predict when an employee will leave but rather show you the likelihood of resignation in that current moment based on specific variables. From the dataset, we were given ratings for each employee on the below factors:

* Education
* Environment Satisfaction
* Job Involvement
* Job Satisfaction
* Performance Rating
* Relationship Satisfaction
* Work Life Balance

Education was ranked 1-5, 1 being "Below College" and 5 being "Doctor." Environment Satisfaction was ranked 1-4; "Low" to "Very High." Job Involvement, Job Satisfaction, Performance Rating, Relationship Satisfaction, Work Life Balance all had similar 1-4 rankings, with 1 being "Low" and 4 being "Very High/Outstanding."

Other more straight-forward data points we were given were Age, Gender, Marital Status, Job Title, Travel Time and Years Spent in Position. Most importantly, we were also given each employees Monthly Income and a Yes/No of whether they attrited or not.

## Conclusions:
When you review the data and make standard charts and graphs, you can see that there is no single variable which determines attrition rates. Machine learning techniques also confirmed this by showing a very broad importance value range for many different variables. Through our exploration of several different machine learning models, we were able to conclude that using a regression model such as Lasso produced too much overfit for our particular dataset. We selected the Gradient Booster model as the best fit for this data due to its unique approach to correcting for overfit in complex questions such as this one. While there is no one factor which determines attrition in this dataset, the most significant factor by a very small margin is Monthly Income - meaning that most of the people who left the company made less than the overall average monthly income and most of those who stayed made more than the monthly average salary. Our Gradient Boosting Model enables us to use the outliers to predict using all of the measured variables and not just that single variable. 


## Data Source:  
* https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset

## Boostrap Source:
* Template Name: Multi
* Template URL: https://bootstrapmade.com/multi-responsive-bootstrap-template/
* Author: BootstrapMade.com
* License: https://bootstrapmade.com/license/

## Other Sources:
* https://corporatefinanceinstitute.com/resources/careers/jobs/attrition-2/

## Image Sources:
* Image 1:  https://www.patriotsoftware.com/wp-content/uploads/2019/03/part-time-vs-full-time-employment-RS13776-compressor.jpg
* Image 2:  https://images.idgesg.net/images/article/2019/08/thumbs-up_happy-employees_binary_diversity_motivated-staff_happy-people_by-peopleimages-getty-100809698-large.jpg
* Image 3:  https://www.bonneystaffing.com/wp-content/uploads/2017/02/AdobeStock_1381193302.jpg

