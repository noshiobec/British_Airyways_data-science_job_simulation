## British Airways Customer Insight Analysis and Predictive Modelling Project

<p style="text-align: justify;">
    This project showcases my involvement in a virtual internship job simulation with British Airways, focusing on showcasing the contribution of data science to the airline's overall success. It involved scraping and analyzing vast volumes of customer review data to derive actionable insights, providing an invaluable understanding of customer preferences and sentiments. Additionally, a predictive model was meticulously crafted and refined to discern the intricate factors influencing purchasing behaviour, ultimately empowering British Airways to make informed strategic decisions that drive enhanced customer satisfaction and sustainable business growth. The job simulation was divided into two tasks; 
</p>

* Task 1: Web scraping to gain company insights
* Task 2: Predicting customer buying behaviour

## Task 1: Web scraping to gain company insights

![image](https://github.com/noshiobec/British_Airyways_data-science_job_simulation/assets/96450822/5547396f-9ea1-40ec-baa6-def29595e629)

### Introduction:
This task involves gathering and analysing customer feedback sourced from the web. The aim is to extract valuable insights from this dataset to enhance strategic decision-making within the organization and elevate customer satisfaction levels. **The Python codes and presentation of findings can be found in the GitHub files in this repository.**

### Scraping Data from Skytrax Reviews:
In this phase, data was extracted from Skytrax reviews, specifically focusing on feedback related to British Airways. Utilizing Python code provided in the Jupyter Notebook, a comprehensive dataset was compiled, encompassing various customer sentiments and experiences with the airline. This process involved extracting text-based reviews, ratings, and other relevant information from Skytrax, ensuring a robust and diverse dataset for analysis.

### Cleaning and Analyzing Customer Feedback Data:
Following the data collection phase, the dataset underwent thorough cleaning and analysis. Measures were taken to ensure data quality and integrity, including removing duplicates, handling missing values, and standardizing text formats. Subsequently, advanced analytical techniques such as topic modelling, sentiment analysis, and word clouds were applied to delve into the dataset. These analyses revealed valuable insights into customer sentiments, preferences, and pain points, providing actionable information for enhancing the airline's services and addressing customer needs effectively.

### Analysis and Insights:

1. The analysis indicates that customer reviews encompass various aspects of the flight experience, offering a comprehensive overview of passengers' perceptions and experiences.

2. Positive Aspects based on sentiment score of words: Excellent (0.26), Nice (0.20), Friendly (0.19), Comfortable (0.15), Lounge (0.15), Drinks (0.14), Cabin (0.12), Crew (0.15). These positive sentiments reflect key areas where the airline excels in delivering a satisfactory customer experience.

3. Areas of Concern: Poor (0.02), Customer (0.02), Delayed (0.04), Due (0.06), Old (0.06), Last (0.06), Two (0.07), and Luggage (0.07). These aspects highlight specific areas where improvements are needed to address customer dissatisfaction and enhance overall service quality.

4. Addressing concerns related to delays, luggage, and overall customer service is crucial for enhancing the overall travel experience and customer satisfaction. By prioritizing improvements in these areas, the airline can effectively address customer feedback and elevate the quality of service provided.

5. Importantly, many positive reviews do not result in recommendations, emphasizing the need to align with customer expectations for a more recommendable experience. Understanding and meeting customer expectations is essential for fostering positive word-of-mouth and driving recommendations, even in the presence of positive feedback.


## Task 2: Predicting customer buying behaviour

![image](https://github.com/noshiobec/British_Airyways_data-science_job_simulation/assets/96450822/9be39b6b-9890-41cc-8fd0-cfabe89e3837)

### Introduction:
This task involves delving into the realm of predictive modelling to anticipate customer buying behaviour, which is crucial for British Airways to acquire customers before they embark on their holidays. Leveraging data and predictive models, the objective is to understand the intricate patterns and factors influencing customers' purchasing decisions, ultimately enhancing proactive customer acquisition strategies.

### Exploring and Preparing the Dataset:
During this phase, the provided customer booking data is meticulously explored and prepared, laying the foundation for building a high-quality predictive model. Through thorough examination and manipulation of the dataset, key features and variables that significantly influence customer buying behaviour are identified. Additionally, consideration is given to creating new features to augment the predictive power of the model, thereby setting the stage for robust predictive analytics.

### Training a Machine Learning Model:
With the dataset meticulously prepared, a machine learning model capable of predicting the target outcome is trained. Utilizing algorithms conducive to providing insights into variable contributions, such as RandomForest and Logistic regression to discern and interpret the underlying patterns and factors driving customer purchasing decisions.

### Analysis and Insights
1. Total Entries: 50,000 before cleaning, 49,281 after cleaning and 14 features. 
2. Feature Importance: Purchase lead had the highest feature importance while trip type, seats, extra luggage, food, and sales channel contributed the least.
3. Model Performance: Random Forest consistently outperforms Logistic Regression in overall accuracy across different sampling techniques and Logistic regression demonstrates superior F1-scores for predicting completed 
   bookings in class 1, highlighting its effectiveness in capturing positive instances.
4. Travel Preferences:
    * Highest number of passengers: 1
    * More interest in extra luggage, less in inflight meals and preferred seats
    * Internet as the predominant trip channel
    * Roundtrip bookings significantly outnumber other types
5. Geographic Insights:
    * Australia: Highest customer booking visits
    * Malaysia: Highest number of completed bookings
6. Temporal Trends:
    * More booking visits on weekdays
    * Minimal difference in completed bookings across weekdays
7. Flight Details:
    * Most common flight duration: 8.5-9 hours (average: 8.83 hours)
    * Route 'AKLKUL' records the highest bookings
    * Completed bookings constitute 15% of the dataset

