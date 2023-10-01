# Lead Scoring Case Study
## Synopsis:
This analysis is conducted for X Education with the objective of increasing enrollment of industry professionals in their courses. The provided dataset offers valuable insights into how potential customers interact with the website, the time they spend on it, and the various channels through which they arrive at the site, all in relation to the conversion rate.

## Problem Statement:
X Education, an online education provider, caters to industry professionals seeking online courses. Daily, numerous professionals visit their website to explore available courses. The company markets its courses on various platforms, including search engines like Google. Upon landing on the website, visitors may browse courses, fill out course inquiry forms, or watch instructional videos. When visitors provide their email addresses or phone numbers while filling out forms, they are categorized as leads. Additionally, the company acquires leads through referrals. Subsequently, the sales team initiates contact via calls and emails. While some leads are converted, most do not convert, with X Education's typical lead conversion rate standing at approximately 30%.

Currently, X Education faces a challenge in converting a significant portion of its leads. For instance, out of 100 leads acquired in a day, only about 30 are converted. To enhance this process, the company aims to identify the most promising leads, referred to as 'Hot Leads.' Identifying these leads is expected to increase the lead conversion rate, as the sales team can then focus more on communicating with potential leads rather than reaching out to everyone indiscriminately.

As depicted, there is a substantial influx of leads in the initial stage, but only a fraction eventually becomes paying customers at the bottom. In the middle stage, nurturing potential leads (e.g., providing product information, maintaining constant communication) is crucial to achieving a higher lead conversion rate.

X Education has tasked you with helping them select the most promising leads—those with the highest likelihood of conversion into paying customers. The company requires you to build a model that assigns a lead score to each lead. Leads with higher scores are more likely to convert, while those with lower scores are less likely. The CEO has set a target lead conversion rate of around 80%.

## Data:
You have access to a dataset containing approximately 9000 data points related to leads. This dataset comprises various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc., which may be relevant in determining lead conversion. The target variable, 'Converted,' indicates whether a lead was converted (1) or not (0). You can refer to the data dictionary provided in the zip folder for more information about the dataset. Additionally, please note that many categorical variables contain a level called 'Select,' which must be handled as it is effectively a null value.

## Goals of the Case Study:
This case study has several objectives:

1. Build a logistic regression model to assign a lead score ranging from 0 to 100 to each lead. This score will help the company target potential leads effectively, with higher scores indicating hotter leads more likely to convert and lower scores indicating colder leads with lower conversion potential.

2. Address any additional problems presented by the company as your model evolves. These challenges are documented separately and should be integrated into your recommendations in the final presentation.
