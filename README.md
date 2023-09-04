# HealthCare-Cost-Analysis
## Abstract
Dataset of personal medical data of 1,338 patients with a variety of variables that have an affect on the cost of medical services provided. The purpose of the analysis is to analyze the effects of variables on the cost of medical care, e.g. age, gender, region, etc.
## ERD
![228036499-add02f0a-54b8-4a90-90f9-47e71c843ef0](https://github.com/anuragsrivastav-dtu/HealthCare-Cost-Analysis---Statistics-and-SQL/assets/140643875/d0524ddd-4e18-458c-bcd8-d3bdf589c3ba)
Variables
## Variables
There are a variety of variables that will impact the outcome of this analysis:
Age: age of primary beneficiary
Teen:13-19
Adult: 20-39
Middle Age Adult : 40-59
Senior Adult :60+
Sex: insurance contractor gender,
Male
Female
Body Mass Index (BMI): Weight to height body mass ratio
Underweight: Below 18.5
Normal: 18.5 - 24.9
Overweight: 25.0 – 29.9
Obese: Greater Than or equal to 30.0
Children: Number of dependents
Smoker: Smoking
Region: Region of domicile of the patient in the United States.
Northeast
Southeast
Southwest
Northwest
Charges: Individual medical costs billed by health insurance for services provided
## Objective
The objective of the analysis is to analyze the effects of variables on the cost of medical care. The analysis seeks to answer the following questions:

1 Which region has the lowest cost of medical care?
2 Which gender has the highest typical medical charges?
3 Is there correlation between the number of dependents a patient has and medical charges?
4 Is there correlation between age and medical charges?
5 Do individuals with higher BMI have higher medical charges?
6 What is the relationship between smoking and medical charges?
## Analysis
1 What region has the lowest cost of medical care?
![227813514-97acd1b2-554a-4b28-a397-bf3424d2fed6](https://github.com/anuragsrivastav-dtu/HealthCare-Cost-Analysis---Statistics-and-SQL/assets/140643875/759862ef-8de5-4a37-832e-be9745732530)

The overall average of charges in the dataset is $13,270.42. However, there is an uneven distribution of charges in the dataset. As indicated in the histogram above there is a right skew that is affecting the average. The median charge, $9,377.90, is a better indication of the amount of a typical medical charge.
![227813527-8c016af7-cbef-4218-a31c-87a211c04608](https://github.com/anuragsrivastav-dtu/HealthCare-Cost-Analysis---Statistics-and-SQL/assets/140643875/21332c02-b351-4d30-8216-b4043b8d629a)

The same is true for the distribution of charges in the four regions in the dataset. As aforementioned the median is a better indication of the typical medical charge within each region. The Southwest region has the lowest median charge, $8,798.59, of all the regions in the dataset. This can be attributed to the Southwest region having the least amount of smokers, 58, overall, the least amount of female smokers, 21, in the dataset, and the second smallest amount of male smokers, 37, in the dataset. This is significant due to smokers incurring charges that are four times greater than non-smokers on average!

2 Which gender has the highest highest typical charges?
The distribution of the charges of both male and females have a right skew in which outliers are impacting the calculation of the average charges.
![227813596-335b759e-2ef1-4b87-a8e4-2577365f2c70](https://github.com/anuragsrivastav-dtu/HealthCare-Cost-Analysis---Statistics-and-SQL/assets/140643875/da18ccba-4e12-4b3e-81e8-1c74a7202fc8)

The median charges of each sex is a better indicator of the typical charges. Males have a median charge of $9,369.62 and females have a median charge of $9,412.96 as indicated in the bar ch art above.

3 Is there correlation between the number of dependents a patient has and medical charges?
![227813660-5b866f7b-e106-4894-82db-bb04e728f5fb](https://github.com/anuragsrivastav-dtu/HealthCare-Cost-Analysis---Statistics-and-SQL/assets/140643875/8c3e220e-eca5-43b5-b0cb-a194cc52074f)

As indicated in the scatter plot above there is no linear correlation between number of dependents and charges. The correlation coefficient of comparing the number of children a patient has to charges incurred is .07, indicating that there is no correlation. This is also evident in the line of best fit seen on the scatter plot above.

4 Is there correlation between age and medical charges?
![227813708-e345d892-2907-4b04-b49f-41ad5c887c93](https://github.com/anuragsrivastav-dtu/HealthCare-Cost-Analysis---Statistics-and-SQL/assets/140643875/156fe0a0-0c20-4104-8d13-89a13cef29b0)

There is a low correlation between age and charges incurred by patients. This is indicated by the correlation coefficient of 0.30 as well as the line of best fit in the scatter plot above. This is also indicated in the average charges of each age category as well. Teens have an average medical charge of $8,407.35, Adults have an average charge of $10,603.65, Middle Aged Adults have an average medical charge of $15,431.97, and Seniors have an average medical charge of $21,248.02. There is a clear pattern of increased cost as the age of the patient increases.

5 Do individuals with higher BMI have higher medical costs?
![228240332-e56641f0-ab72-493a-881e-76ea344d7e6f](https://github.com/anuragsrivastav-dtu/HealthCare-Cost-Analysis---Statistics-and-SQL/assets/140643875/0f6e4420-da7b-493c-adc4-26787d9f07c4)

Yes, individuals with higher BMIs have higher medical costs. The higher a patient’s BMI the higher the average charges as indicated in the line chart above.

6 What is the relationship between smoking and medical charges?
![228288741-6e1fb81a-3d11-4d60-8830-7e6368f330aa](https://github.com/anuragsrivastav-dtu/HealthCare-Cost-Analysis---Statistics-and-SQL/assets/140643875/878e3c85-c4e1-4f28-b385-26c6520e2a62)

Smoking adversely impacts medical charges. As indicated in the bar chart above smokers have an average charge of $32,050.23 and non-smokers have an average medical charge of $8,434.27. Smokers have an average charge that is nearly four times greater than the amount of non-smokers.
![228288798-d75c2e8a-ea63-4074-971b-0d0a4c3237bf](https://github.com/anuragsrivastav-dtu/HealthCare-Cost-Analysis---Statistics-and-SQL/assets/140643875/358215ce-8b66-4839-8ac4-533a48ba6341)

As seen in the histogram above, the distribution of charges of smokers is bimodal. The two modes are indicative of the subgroups related to BMI. There are two subgroups, patients that have a BMI less than 30 and patients that have a BMI greater than 30. Recall that a BMI over 30 is categorized as obese and a BMI less than 30 is categorized as not obese.
![228288898-2607831d-6515-4d4e-b9e0-3287ce04039e](https://github.com/anuragsrivastav-dtu/HealthCare-Cost-Analysis---Statistics-and-SQL/assets/140643875/9860d323-1cd2-4478-b0b0-b1100e2e90ba)

In the histogram above there is a slight right skew. So, the median is a better indication of the typical charge of a smoker that has a BMI of less than 30. The median charge is $20,167.34.
![228289038-4c2f6115-fc20-41c2-a619-4ea103fbb3aa](https://github.com/anuragsrivastav-dtu/HealthCare-Cost-Analysis---Statistics-and-SQL/assets/140643875/d1600370-228d-475d-887e-34923fb64e10)

The histogram above shows an even distribution of charges with very few outliers. The average charge for smokers with a BMI greater than 30 is $41,557.99.
