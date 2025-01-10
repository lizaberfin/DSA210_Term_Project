# DSA210_Term_Project: Exploring the Relationship Between Step Count and Instagram Activity

Liza Berfin İnce
30719

### Motivation
This project stems from my curiosity about how my digital habits, particularly Instagram engagement, relate to my physical activity. By analyzing these two aspects of my lifestyle, I aim to uncover patterns or correlations that could offer insights into how one influences the other. Additionally, this project serves as an opportunity to apply data science techniques to real-world data, helping me refine my skills in data cleaning, analysis, and machine learning.

### Data Source
**1) Step Count Data:** This dataset was exported from the Apple Health app, which automatically tracks physical activity using sensors on my device. It includes daily step counts over a defined time period and was exported as a CSV file for analysis. Only the necessary columns were retained to focus on the key metrics of physical activity.

**2) Instagram Engagement Data:** This dataset was downloaded directly from Instagram in JSON format. It contains detailed logs of interaction such as likes. The raw data was preprocessed to retain daily totals of interactions, simplifying the dataset while preserving its essential information.

Both datasets were aligned to cover the same time period, enabling a cohesive and comparative analysis to explore the relationship between physical and digital behaviors.

### Data Analysis
**1) Data Cleaning and Preparation:**

- For the Instagram data:
Converted the JSON file into CSV format for easier manipulation and analysis.
Removed unnecessary fields and ensured all missing or duplicated records were handled.

- For the step count data:
Verified the integrity of the dataset, ensuring there were no gaps or inconsistencies in daily step counts.
The two datasets were merged based on their shared Date field to allow direct comparison of daily metrics.

**2) Correlation Analysis:**

- Used statistical correlation metrics (e.g., Pearson correlation coefficient) to explore the relationship between daily step counts and Instagram engagement levels.
- Investigated patterns where increases or decreases in one variable corresponded to changes in the other.

**3) Exploratory Data Analysis (EDA) and Visualization:**
- Computed descriptive statistics, such as means, medians, ranges, and standard deviations, to summarize both datasets.
- Created scatterplots, line graphs, and heatmaps to visually identify trends and patterns.
- Compared activity levels across different contexts, such as weekdays vs. weekends and high-activity vs. low-activity days.

**4) Machine Learning:**
- Applied linear regression to predict step counts based on Instagram engagement and temporal features like day of the week.
- Used clustering techniques, such as K-Means, to group days with similar behaviors in terms of activity and engagement.
- Evaluated model performance using metrics like Mean Squared Error (MSE) and R² to assess predictive power.

### Findings

**Physical and Digital Interaction:**
- There were noticeable patterns where high Instagram engagement days coincided with lower physical activity, suggesting that increased time spent on social media might reduce opportunities for movement.
- Conversely, days with higher step counts often showed reduced Instagram interactions, potentially indicating busier schedules or activities that prioritized physical over digital engagement.

**Temporal Patterns:**
- Weekends tended to have higher Instagram activity but lower step counts, reflecting possible relaxation or leisure-focused behaviors.
- Weekdays exhibited a more balanced trend, with moderate step counts and Instagram engagement.
  
**Correlation Insights:**
- A moderate negative correlation was observed between Instagram engagement and step counts, highlighting a potential inverse relationship. However, this correlation varied across specific time periods, suggesting that other factors might also influence these behaviors.

### Limitations and Future Works
**- Limitations:**
I could not obtain detailed Instagram usage time data. As a result, the analysis was conducted at a daily level, which limits the ability to capture how Instagram engagement and physical activity interact throughout the day. Intra-day patterns, such as specific times of heightened activity or engagement, were not explored.  Since this data is specific to my own habits, the results are personal and may not be applicable to a wider audience without additional data from other individuals. 

**- Future Work:**
To provide a more comprehensive analysis, incorporating additional metrics such as Instagram screen time, app usage logs, or fitness data like distance walked and calories burned would enhance the depth of the study. Exploring time-of-day patterns could reveal how Instagram engagement fluctuates alongside physical activity throughout the day, offering insights into intra-day behavioral trends. Advanced techniques, such as experimenting with deep learning models like LSTMs or GRUs, could help capture temporal dependencies within the data, while classification models might predict whether a day is likely to be "high engagement" or "low engagement" based on features like step count. Expanding the analysis to include data from multiple individuals would uncover broader trends and provide a more generalizable understanding of the relationship between digital engagement and physical activity. Ultimately, these findings could be used to develop actionable recommendations for achieving a healthier balance between digital and physical activities.

