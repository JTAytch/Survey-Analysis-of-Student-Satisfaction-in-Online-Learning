# Survey-Analysis-of-Student-Satisfaction-in-Online-Learning
Survey Analysis of Student Satisfaction in Online Learning

Eliana Alon | Lauren Furman | Joseph Aytch | Michelle Valencia 

DSC450 Applied Data Science 
Fall 2024 


Domain:
The focus on student satisfaction in online learning is to evaluate these areas to provide a comprehensive understanding of student satisfaction in online learning and identifying strengths and weaknesses for improvement. 
Course Content: Availability of resources (e.g., readings, videos). Clarity of materials.
https://www.kaggle.com/datasets/mdmahmudulhasansuzan/students-adaptability-level-in-online-education


Instructor Effectiveness: Communication skills and responsiveness. Teaching methods, engagement strategies, and availability for support/feedback.
https://www.kaggle.com/datasets/vikantkumar/e-learning-student-dataset


Technology and Platform Usability: Ease of use of the online learning platform.  Reliability and accessibility of technology (e.g., software, tools)https://www.kaggle.com/datasets/sujaradha/online-education-system-review

Student Engagement: Participation in discussions and group work. Opportunities for interaction with peers and instructors.  https://www.kaggle.com/datasets/mdmahmudulhasansuzan/students-adaptability-level-in-online-education 

Technical Support Services: Availability for academic support (e.g., tutoring, writing centers). Technical support and troubleshooting. Including mental health and wellness resources. 
https://digitalrepository.unm.edu/ulls_fsp/190/
  https://www.kaggle.com/datasets/sujaradha/online-education-system-review
Learning Outcomes: Perceived value of the learning experience. Application of skills and knowledge gained.
https://www.kaggle.com/datasets/septa97/100k-courseras-course-reviews-dataset/data


Flexibility and Convenience: Scheduling and time management. Work-life balance. Opportunities for asynchronous vs. synchronous learning. 
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9968937/

Peer Interaction: Opportunities for networking and collaboration. Sense of belonging and community within the online environment.  Including feedback/collaboration on group projects.  https://www.kaggle.com/datasets/vikantkumar/e-learning-student-dataset

Assessment and Feedback: Clarity of assessment criteria and expectations. Fairness and transparency in grading. 
https://www.kaggle.com/datasets/vikantkumar/e-learning-student-dataset
https://www.kaggle.com/datasets/mdmahmudulhasansuzan/students-adaptability-level-in-online-education


Overall Satisfaction: Overall satisfaction with online learning. Likelihood of recommending. Also, suggestions for improvement.
https://www.kaggle.com/datasets/sujaradha/online-education-system-review


Dataset:
The dataset for this project is a student feedback dataset that includes details on students’ adaptability to online education, their satisfaction levels, and other relevant factors. 
Data Fields:
Education Level – The level of education the student is pursuing. 
Institution Type – Type of institution (e.g., public, private).
Gender – Student Gender.
Age – Student’s Age.
Device – The device used for online education (e.g., laptop, tablet).
IT Student – Whether the student is an IT student or not.
Location – Student’s Location.
Financial Condition – Student’s financial condition.
Internet Type – Type of internet connection used. 
Network Type – Type of network connection used.
Flexibility Level – Measure of how flexible the online course is (e.g., asynchronous or synchronous). 

Dataset Location:
The dataset can be located and downloaded from https://www.kaggle.com/datasets/mdmahmudulhasansuzan/students-adaptability-level-in-online-education

Research Questions:

How do different types of internet and network connections impact student satisfaction and adaptability?
What are the differences in satisfaction levels between IT students and non-IT students?
How does the flexibility of online courses (e.g., asynchronous vs. synchronous learning) influence student satisfaction?
What demographic factors (e.g., age, gender, education level) are most strongly associated with student satisfaction in online education?
How does the type of institution (public vs. private) affect student satisfaction with online education?

Benefits:
Improved Student Experience: By understanding the factors that influence student satisfaction, educational institutions can tailor their online education offerings to better meet student needs and preferences.
Enhanced Course Design: Insights from the analysis can help in designing more effective and engaging online courses.
Targeted Support Services: Identifying the impact of support services on student satisfaction can lead to more targeted and effective support for students.
Informed Decision-Making: Educational institutions can make data-driven decisions to improve their online education programs.
Increased Retention Rates: By addressing the factors that influence student satisfaction, institutions can improve retention rates and reduce dropout rates.
Better Resource Allocation: Understanding the relationship between financial conditions and satisfaction can help institutions allocate resources more effectively to support students in need.
 
Method:
To analyze the dataset effectively, the following methods will be employed: 
Data Preprocessing:
Data Cleaning: Handle missing values, remove duplicates, and correct any inconsistencies in the dataset.
Data Transformation: Convert categorical variables into numerical values using techniques like one-hot encoding.
Normalization: Normalize numerical data to ensure all features contribute equally to the analysis.
Exploratory Data Analysis (EDA):
Descriptive Statistics: Calculate mean, median, mode, standard deviation, and other relevant statistics for each feature.
Visualization: Create visualizations (e.g., histograms, box plots, scatter plots) to understand the distribution and relationships between variables.
Sentiment Analysis:
Text Processing: Preprocess textual feedback (e.g., tokenization, stop-word removal, stemming).
Sentiment Scoring: Use sentiment analysis tools to assign sentiment scores to student feedback.
Keyword Extraction:
Text Mining: Apply text mining techniques to extract frequently mentioned keywords and phrases from student feedback.
Statistical Analysis:
Correlation Analysis: Calculate correlation coefficients to explore relationships between variables (e.g., device type and satisfaction).
Hypothesis Testing: Conduct hypothesis tests to determine the significance of observed patterns and relationships.
Comparative Analysis:
Group Comparisons: Compare satisfaction levels across different groups (e.g., IT students vs. non-IT students, public vs. private institutions) using t-tests or ANOVA.
Regression Analysis:
Model Building: Build regression models to predict student satisfaction based on various features (e.g., financial condition, internet type).
Model Evaluation: Evaluate model performance using metrics such as R-squared, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).
Clustering:
Segmentation: Apply clustering algorithms (e.g., K-means, hierarchical clustering) to segment students based on their adaptability and satisfaction levels.
 Potential Issues:

Data Quality:
Missing or Incomplete Data: Missing values or incomplete records can skew the analysis and lead to inaccurate conclusions.
Inconsistent Data: Inconsistencies in data entry (e.g., different formats for dates or categorical variables) can complicate data preprocessing and analysis.
Bias in Data:
Sampling Bias: If the dataset is not representative of the entire student population, the findings may not be generalizable.
Response Bias: Students who are more dissatisfied or more satisfied may be more likely to provide feedback, leading to biased results.
Privacy and Ethical Concerns:
Data Privacy: Ensuring that student data is handled in compliance with privacy regulations (e.g., FERPA) is crucial.
Ethical Use of Data: Using student data ethically and ensuring that the analysis does not harm or disadvantage any group of students.
Interpretation of Results:
Correlation vs. Causation: Identifying correlations between variables does not imply causation. Care must be taken not to overinterpret the results.
Complex Interactions: The relationships between variables may be complex and multifaceted, requiring sophisticated analysis techniques to understand fully.
Technical Challenges:
Data Integration: Combining data from different sources or formats can be technically challenging and time-consuming.
Scalability: Handling large datasets efficiently requires robust computational resources and techniques.
Generalizability:
Context-Specific Findings: Results may be specific to the context of the dataset and may not be applicable to other educational settings or populations.
  
Conclusion:

In summary, this project seeks to deliver an in-depth analysis of student satisfaction with online education through the use of the Students Adaptability Level in Online Education dataset. By exploring various factors, such as demographics, device usage, financial circumstances, and course flexibility, we aim to reveal critical insights that can assist educational institutions in improving their remote learning offerings. The analysis will utilize a variety of methods, including sentiment analysis, keyword extraction, statistical analysis, and regression modeling, to ensure a comprehensive understanding of the data.
