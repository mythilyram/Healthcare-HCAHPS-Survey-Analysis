# Healthcare-HCAHPS-Survey-Analysis
HCAHPS Patient Survey Analysis - American Hospital Association

### Introduction

The Hospital Consumer Assessment of Healthcare Providers and Systems **(HCAHPS) survey is a standardized tool used to measure patients` perceptions of their hospital experiences** in the United States.
- It was developed by the Centres for Medicare & Medicaid Services (CMS) in collaboration with the Agency for Healthcare Research & Quality (AHRQ).
- **The primary goal of the HCAHPS survey is to collect feedback from patients about their care experiences, to improve the quality of healthcare services provided by hospitals**.

The report was made for Maven Analytics’ Healthcare challenge.

### Role 
Participants were tasked to play the role of a Data Analyst for the American Hospital Association (AHA), a national organization that represents hospitals and their patients and acts as a source of information on healthcare issues and trends.

### Objective

To analyze the Hospital Consumer Assessment of Healthcare Providers and Systems (HCAHPS) survey results for the past 9 years and evaluate whether it has been successful in creating incentives for hospitals to improve their quality of care.

### About The Data Set
- All of the data used in this challenge were provided by Maven Analytics.
- It comprised 7 CSV tables, namely: measures, national_results, questions, reports, responses, state_results, and states.
- A separate CSV table was also provided which serves as a dictionary for the description of each column in each of the 7 CSV tables.
- The survey data spans from 2013 to 2022.
- The survey collects all the measures in 3 categories. Top box percentage (Promoters), Middle Box percentage (passives), and bottom Box percentage (Detractors).
  
### KPI - Net Promoter Score (NPS) 
To analyze the healthcare survey dataset, I`m going to use a Key Metric called NPS.
- It is a widely used metric to measure customer satisfaction and loyalty.
- It is derived from responses to a simple survey question, On a scale of 0 to 10.
- Based on their responses, respondents are categorized into three groups:
  - Promoters (score 9-10): These are enthusiastic customers who are likely to recommend your product or service.
  - Passives (score 7-8): These customers are satisfied but not enthusiastic. They are unlikely to actively promote your product but are also unlikely to speak negatively about it.
  - Detractors (score 0-6): These customers are unhappy and may actively discourage others from using your product or service.

The NPS is then calculated by subtracting the percentage of Detractors from the percentage of Promoters. 
- The formula is as follows:
> NPS=%Promoters−%Detractors
- NPS can range from -100 to +100, with positive scores indicating a higher likelihood of customer recommendation and negative scores suggesting room for improvement.
- NPS is a relative metric, and the score alone might not provide a comprehensive understanding of customer satisfaction.
- It is often more valuable when tracked over time or compared to industry benchmarks.

### Analysis

The primary concept of the report is to showcase the trends and impacts of the HCAHPS survey over the years.
I chose to focus solely NPS score. My goal was to determine if patient satisfaction and loyalty increased or decreased over the past 9 years. 

**Overview: **
- Total hospital count - 5251
- Total number of completed surveys - 43.2 K
- Average Response rate - 26.6%
- NPS 62.9%

## Heat map visual with tooltip

- I have created a heat map visual showing the distribution of NPS for each measure over the years with a tooltip to easily visualize this trend.
- It is evident from the heat map that the NPS score of most of our measures has seen an increasing trend from 2014 to 2020.
- We can see a clear change in shift by the year 2020 which could be attributed to COVID-19 and hence a shift in patients' sentiments.
- But the measures - "Quietness of the hospital" and "Communication with the Doctors" show a continued decrease. This could be something to research further.

![image](https://github.com/mythilyram/Healthcare-HCAHPS-Survey-Analysis/assets/123518126/ff4eddbc-96b6-430d-9421-6cb5e5bd70ea)

## NPS trend 

- The Line chart shows the trend of NPS over the years for each type of measure.
- The Global items (Willingness to recommend the hospital and Overall hospital rating) have the highest NPS scores with 66.2% & 64.1% respectively.
- The Individual Items (Quitenes and Cleanliness of the hospital) have the lowest scores.
- Among the Composite measures, Care Transition and communication about medication have lower NPS scores of 47.4%. Discharge info and communication with Doctors and nurses faired the top scores with scores higher than 70%

![image](https://github.com/mythilyram/Healthcare-HCAHPS-Survey-Analysis/assets/123518126/5afce074-1f13-48db-aeae-18f877d2ed20)


## Top Promoters/Detractors

- I have used **Bookmark** to study Promoters or Detractors using a **Shape map, top 5 States matrix and Top Region matrix**. The other visual can be accessed by the show button.
- The color Saturation on the Shape map indicated by the value of Promoters or Detractors

![5](https://github.com/mythilyram/Healthcare-HCAHPS-Survey-Analysis/assets/123518126/92924788-8f91-4327-955b-8a5552fdb97c)
![4](https://github.com/mythilyram/Healthcare-HCAHPS-Survey-Analysis/assets/123518126/9cfe0c80-6ce3-41ef-adfc-fd5f56e33a25)

- Helps to study the data by state or by region.

![4 5](https://github.com/mythilyram/Healthcare-HCAHPS-Survey-Analysis/assets/123518126/b3c74076-f66f-4a05-88af-cc90f9e31304)


 ## Top/Bottom States by response rate is represented by bar graphs

![6](https://github.com/mythilyram/Healthcare-HCAHPS-Survey-Analysis/assets/123518126/da901b82-7ee5-4c35-8049-06b5b752a460)

## Final Dashboard

![image](https://github.com/mythilyram/Healthcare-HCAHPS-Survey-Analysis/assets/123518126/e9326818-06ca-40b0-8abb-f73b3c825138)



