# Sleep Efficiency

**Sleep Efficiency Dataset Analysis Report**

**Introduction:**
This report presents an analysis of a dataset containing information about the sleep patterns of a group of test subjects. The dataset includes various factors such as age, gender, bedtime, wakeup time, sleep duration, sleep efficiency, sleep stages, awakenings, caffeine and alcohol consumption, smoking status, and exercise frequency. The goal of this analysis is to gain insights into the sleep patterns and factors affecting sleep efficiency among the test subjects.

**Data Overview:**
The dataset comprises 452 observations and 15 columns. The columns include:
1. ID: Unique identifier for each test subject.
2. Age: Age of the test subject.
3. Gender: Gender of the test subject.
4. Bedtime: Time when the test subject goes to bed.
5. Wakeup time: Time when the test subject wakes up.
6. Sleep duration: Total amount of time the test subject slept (in hours).
7. Sleep efficiency: Proportion of time spent in bed that is actually spent asleep.
8. REM sleep percentage: Percentage of time spent in REM sleep.
9. Deep sleep percentage: Percentage of time spent in deep sleep.
10. Light sleep percentage: Percentage of time spent in light sleep.
11. Awakenings: Number of times the test subject wakes up during the night.
12. Caffeine consumption: Amount of caffeine consumed (in mg) in the 24 hours prior to bedtime.
13. Alcohol consumption: Amount of alcohol consumed (in units) in the 24 hours prior to bedtime.
14. Smoking status: Smoking status of the test subject.
15. Exercise frequency: Frequency of exercise (in days per week).

**Analysis and Insights:**
1. **Sleep Duration Distribution by Gender:**
   - The analysis revealed that there is variation in sleep duration between different genders. While this analysis provides an overview, further investigation into potential factors influencing this difference is warranted.

2. **Correlation Between Numerical Features:**
   - The correlation heatmap showed relationships between various numerical features. For example, there was a positive correlation between sleep duration and deep sleep percentage, indicating that longer sleep durations tend to be associated with a higher percentage of deep sleep.

3. **Sleep Efficiency vs. Age:**
   - The scatter plot of sleep efficiency against age showed no clear pattern or correlation. However, additional subgroup analysis based on age ranges could provide more insights into age-related trends in sleep efficiency.

4. **Distribution of Sleep Stages:**
   - The kernel density plot illustrated the distribution of REM, deep, and light sleep percentages. This visualization can help understand the typical distribution of sleep stages among the test subjects.

5. **Effect of Caffeine Consumption on Sleep Efficiency:**
   - The bar plot demonstrated the potential impact of caffeine consumption on sleep efficiency. Subjects with higher caffeine consumption tended to have lower sleep efficiency, suggesting a possible negative relationship between caffeine intake and sleep quality.

**Conclusion:**
In conclusion, this analysis provides valuable insights into the sleep patterns and factors affecting sleep efficiency among the test subjects. Further exploration and hypothesis testing could help validate these findings and provide deeper understanding. Additionally, incorporating machine learning models for predictive analysis could help identify key predictors of sleep efficiency and potentially aid in personalized sleep management strategies.

Dataset Link: https://www.kaggle.com/datasets/equilibriumm/sleep-efficiency/data
