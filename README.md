# Data-Survey-Analysis


In this project, I started by importing data from an Excel file, which contained valuable information that needed to be analyzed. To prepare the data for analysis, I utilized the powerful data manipulation capabilities of the Python library Pandas.

One of the key steps involved in the data preparation phase was unpivoting or melting the data. The original dataset was in a wide format, with each question occupying a separate column. By using Pandas, I transformed the data into a long format. This transformation allowed for a more flexible and granular analysis, as it organized the data in a way that each observation represented a single response to a specific question.

Once the data was in the melted format, I focused on extracting insights regarding the number of respondents and the number of individuals who answered the same question. By aggregating the data based on unique identifiers, such as respondent IDs or question IDs, I calculated the counts and frequencies of responses. This provided a clearer understanding of the distribution of responses across different questions and allowed for deeper analysis. During the analysis, I also encountered scenarios where questions and subquestions were separated into different columns. 

I transformed data to combine related questions and subquestions into a single column to address this. This consolidation simplified the analysis process and allowed for a more comprehensive examination of the data. Throughout the project, I ensured the accuracy and integrity of the data by performing data-cleaning tasks, such as handling missing values, correcting inconsistencies, and formatting the data appropriately. By combining the data import from Excel, unpivoting the data using Pandas, calculating respondent and response counts, and consolidating questions and subquestions, I could comprehensively analyze the dataset. This analysis provided valuable insights into the behavior and preferences of respondents, as well as patterns and trends within the data.

Overall, this project demonstrated the power of data manipulation using Pandas. Combining these techniques allowed for a deeper understanding of the dataset and enabled informed decision-making based on the insights obtained.

This project utilized data and guidance from Shashank Kalanithi's YouTube channel. The data for the project was obtained from the GitHub repository (**[https://github.com/kshashank03/Survey-Monkey-Tutorial](https://github.com/kshashank03/Survey-Monkey-Tutorial)**), which provided valuable resources and instructions for the analysis.
