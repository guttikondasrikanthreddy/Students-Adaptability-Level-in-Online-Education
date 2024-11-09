**Short Description**
This project investigates students' adaptability to online education during the COVID-19 pandemic using big data tools and machine learning algorithms. Leveraging a dataset of survey responses collected from Kaggle.

**Overview**
The COVID-19 pandemic forced a rapid shift from traditional in-person education to online learning, presenting challenges for students across the world. This project aims to assess how well students adapted to this change by analyzing survey data with big data processing and machine learning methods. By identifying patterns in adaptability based on factors like age, internet connectivity, financial status, and learning devices, this study provides insights that educational institutions can leverage to improve remote learning experiences.

**Research Question**
How well have students adapted to online education, and what factors contribute to high or low adaptability?

**Project Goals**
- Determine adaptability levels of students to online education and identify factors contributing to those levels.
- Predict adaptability levels based on survey data, aiding educational institutions in tailoring online learning formats.
- Visualize and interpret results to help decision-makers understand challenges and support required for effective online learning.

**Data Source**
Dataset: Kaggle
Attributes: 14 categorical attributes and 1,205 observations
Target Variable: Adaptability Level (categorized as Low, Moderate, and High)

**Technologies Used**:
Python: For data preprocessing, initial analysis, and exploratory data visualization.
Google Cloud (Hadoop): Used for data storage and processing, facilitating large-scale data handling.
Spark: Enabled efficient data transformation and processing through MapReduce functions.
Tableau: Visualized adaptability factors through interactive dashboards, highlighting key trends.

**System Architecture**
Data Collection: Survey data collected from Kaggle.
Preprocessing: Data cleaned and transformed in Python, ensuring it was ready for big data processing.
Data Processing: Data uploaded to Google Cloud's Hadoop system and processed using Spark's MapReduce to analyze adaptability levels.
Visualization: Tableau dashboards created to illustrate findings on adaptability trends.

**Results**:
Key findings include:

- Students using mobile devices and mobile data showed lower adaptability.
- Urban students tended to adapt better than rural students, likely due to better internet access.
- Younger age groups (11-15, 16-20) faced more adaptation challenges compared to older students.
- Students in schools and universities demonstrated higher adaptability levels than college students.

**Conclusion**:
This project highlights the adaptability levels of students in online education and the influence of factors like environment, technological literacy, and access to resources. By identifying and addressing these challenges, educational institutions can create supportive online learning environments that foster student resilience and adaptability.

**References**
Suzan, M. H., Samrin, N. A., Biswas, A. A., & Pramanik, A. (2021). Students' Adaptability Level Prediction in Online Education using Machine Learning Approaches. In 2021 12th International Conference on Computing Communication and Networking Technologies (ICCCNT).
