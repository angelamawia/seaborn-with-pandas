# Exploratory Data Analysis of Texas Death Row Inmates (2018)

## Overview
This repository contains an exploratory data analysis (EDA) of a dataset focused on inmates in Texas who were on death row prior to their executions in 2018. The dataset provides insights into various aspects of the inmates' backgrounds, including their last statements, education levels, and racial demographics.

The **"Statement"** column evokes a deep emotional response as it captures the last words shared by these inmates. Many express regret for their offenses, while others reflect on their lives and ask for forgiveness from the families they have affected. Some inmates convey a belief that only God has the authority to take a human life, not fellow human beings. This poignant blend of regret, reflection, and moral contemplation makes the data not just a collection of statistics, but a profound narrative about human experiences and the complexities of justice.

Many thanks to the authorities in Texas for releasing this data, collected to aid research and ensure that the lessons learned from these cases contribute to preventing similar executions in the future.With great respect, I analyze this dataset to uncover the profound stories it tells about human experiences, justice, and the complexities of life and death. 

## Dataset
The dataset is sourced from Kaggle and contains the following columns:
- **Age at Execution**: The age of the inmate at the time of execution.
- **Highest Education Level**: The highest level of education attained by the inmate.
- **Race**: The racial background of the inmate.
- **Last Statement**: The final words written by the inmate before execution.
- **Eye_color**: The eye color of each inmate.
- **Execution date**: The date each inmate was executed.
- **County**: The county from which the inmate belongs.
- **Weight**: The weight of each inmate.
- **Height**: The height of each inmate.
- **Date of offense**: The date which the inmate commited the offense.
- **Date of birth**: The date each inmate was born.
- **Native State**: The state at where each inmate lived.

  
## Analysis
The analysis performed includes:

### 1. Expressions of Humanity: Analyzing the Last Words of Death Row Inmates

![image](https://github.com/user-attachments/assets/81fa6939-d708-4e71-8f40-cf159d00cb20)


This analysis delves into the poignant last statements made by death row inmates, offering a glimpse into their emotional and psychological states in their final moments. The collected data reveals themes of love, family, remorse, and hope. The emphasis on relationships highlights the enduring human need for connection, even in the face of mortality.

**Key Observations:**
- **Longing for Connection**: Many inmates express sentiments around love and family, underscoring the importance of these bonds as they confront their impending fate.
- **Gratitude and Regret**: Common phrases include expressions of thanks and apologies, illustrating a blend of gratitude for life's moments and regret for past actions.
- **Reflections on Life**: The words often reflect a deep consideration of existence, with inmates contemplating the value of their lives and the choices they made.
- **Desire for Understanding**: A notable number of statements reveal a yearning for their stories to be acknowledged, indicating a fundamental human desire to be heard and understood.

This analysis serves as a powerful reminder of the humanity that persists in the most challenging circumstances, urging us to engage with the stories behind the statistics.


### 2. Sentiment Analysis of Last Statements from Death Row Inmates

![image](https://github.com/user-attachments/assets/d843d41a-1898-4380-8183-c2bb30ba45b1)


In this section, we perform a sentiment analysis of the last statements provided by death row inmates, categorizing their expressions into positive, neutral, and negative sentiments. The findings highlight the emotional landscape present in these final words.

**Key Findings:**
- **Predominance of Positive Sentiments**: The positive sentiment category significantly surpasses others, with many inmates articulating hopeful or uplifting emotions, suggesting psychological resilience in dire circumstances.
- **Presence of Neutral Sentiments**: A notable number of statements convey neutrality, indicating some inmates acknowledged their situation without strong emotional engagement, potentially reflecting resignation.
- **Lower Frequency of Negative Sentiments**: The small number of negative sentiments suggests that few inmates expressed overt despair or anger, indicating a possible tendency to focus on positive reflections.

Overall, this sentiment analysis reveals the complexity of emotions that inmates experience, showcasing their resilience, hope, and desire for connection, even in their final moments.


### 3. **Education Level Distribution**
A count plot visualizes the highest education levels attained by inmates. The findings highlight the educational background of those on death row, revealing significant disparities.

![image](https://github.com/user-attachments/assets/d3c43665-fb0d-461f-9d37-e0aaabe26978)


### 4. **Age at Execution**
The general age distribution of inmates at the time of execution is analyzed using histograms, showing the age demographics of death row inmates. 

![image](https://github.com/user-attachments/assets/f70596c1-feb9-4733-b489-bf356e1c636f)

### 5. **Education vs. Age Scatter Plot**
A scatter plot examines the relationship between education levels and ages at execution, colored by race, revealing patterns and insights into how these factors may relate.

![image](https://github.com/user-attachments/assets/5db2a517-15fc-46b7-b9d6-d9db48530bad)


### 6. **Racial Demographics**
The distribution of inmates by race is visualized through bar charts, highlighting racial disparities in the death row population.

![image](https://github.com/user-attachments/assets/43393f43-656a-4619-97a8-3b90d98aeeff)

### 7. **Pairwise Relationships**
A pairplot provides insights into relationships between multiple variables, allowing for a deeper understanding of correlations within the dataset.

![image](https://github.com/user-attachments/assets/d55ecfcd-c95d-43aa-9918-84987d9dd96d)

## Key Findings
- The majority of inmates on death row have lower levels of formal education.
- Age at execution varies, with noticeable peaks at certain age groups.
- Racial demographics show significant disparities, with certain races being overrepresented.

## Conclusion
This EDA provides valuable insights into the profiles of inmates on death row in Texas. The visualizations and analyses can aid in understanding the socio-economic and racial factors contributing to the death penalty.

## Future Work
Further analyses could include:
- A time series analysis of executions over the years.
- A deeper exploration of the relationship between socio-economic status and sentencing.

## Installation
To run the Jupyter notebook and reproduce the analysis:
1. Clone this repository.
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 

## Contact
For inquiries or collaboration, please feel free to reach out via email at angelmawia.01@gmail.com. You can also connect with me on https://www.linkedin.com/in/angela-mawia/ for professional networking and updates on my projects.



