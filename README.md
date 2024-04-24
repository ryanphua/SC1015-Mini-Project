# SC1015-Mini-Project (Diabetes Analysis)

## Context:

Diabetes is a chronic disease in which blood sugar levels are above normal. Over time, if uncontrolled, the high levels of blood sugar can damage nerves and blood vessels, leading to serious health complications such as heart disease, stroke, blindness and amputations.

In 2014, 8.5% of adults aged 18 years and older had diabetes. By 2019, diabetes had become the direct cause of 1.5 million deaths worldwide, with 48% of these deaths occurring before the age of 70. An additional 460,000 deaths due to kidney disease were attributed to diabetes, while raised blood glucose levels were responsible for approximately 20% of cardiovascular deaths. In Singapore, more than 400,000 people in Singapore live with diabetes, with this number projected to rise to 1 million by 2050. 

There are two main types of diabetes. Type 1 diabetes is characterized by the pancreas not producing enough insulin naturally. On the other hand, Type 2 diabetes is characterized by patients being unable to effectively utilize insulin. While Type 1 diabetes usually occurs due to genetic predisposition, Type 2 diabetes is often caused by lifestyle habits, such as excessive consumption of processed sugar, lack of physical activity, and unhealthy eating habits.

The scale and effects of diabetes are devastating, emphasising a need for us to do what we can to keep diabetes at bay. As such, our group has decided to analyse a cleaned copy of data compiled by the Centers for Disease Control and Prevention (CDC). (https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset) The Behavioral Risk Factor Surveillance System (BRFSS) is a health-related telephone survey that is collected annually by the CDC. Each year, the survey collects responses from over 400,000 Americans on health-related risk behaviors, chronic health conditions, and the use of preventative services.

## Content

Our data analysis aims to extract potential higher risk factors that can be present in a person's lifestyle habits, in hopes that people will be able to identify and improve factors that mahy cause an increase the risk of diabetes. We will be further cleaning the data and scoping into the few factors that are more significant in predicting diabetes risk, before further categorising them into numerical, binary and one-hot encoded data to carry out our analysis.

After inspecting the three datasets available to us in the Kaggle link, we decided to make use of the Diabetes Binary dataset with a 50/50 split between respondents having and not having diabetes instead of the other two datasets. This was due to the other two datasets having highly skewed data, where the number of respondents who did not have diabetes was almost 7 times more than those who had diabetes. This would lead to larger inaccuracies when analysing the diabetes risk factors.
