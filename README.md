# Twitter Education Trends Analysis

![Twitter Logo](https://www.logo.wine/a/logo/Twitter/Twitter-Logo.wine.svg)

# Project Overview

Welcome to the Twitter Education Trends Analysis project! In this project, we aim to analyze a vast collection of Twitter data to determine whether Twitter can be considered a credible source of information reflecting important trends in education. We have access to approximately 100 million Tweets, with a focus on topics related to education, schools, universities, learning, and knowledge sharing.

**Data Source:** The Twitter data is stored in Google Cloud Storage at `gs://msca-bdp-tweets/final_project`, with each tweet stored in JSON format. The dataset is extensive, accounting for approximately 500GB of data.

# Technology Stack

In this section, we'll outline the technology stack and tools employed to conduct the Twitter Education Trends Analysis project.

## Google Cloud Platform (GCP)

- **Google Cloud Storage (GCS):** We leverage GCS to store and manage the extensive collection of Twitter data located at `gs://msca-bdp-tweets/final_project`. GCS provides scalability and reliability for data storage.

## Big Data Processing

- **Apache Spark:** Apache Spark serves as the core engine for distributed data processing. It enables us to parallelize and process the massive Twitter dataset efficiently, making it suitable for big data analysis.

- **Parquet Format:** Parquet is a columnar storage format optimized for analytics. We utilize Parquet files to store data efficiently, reducing storage costs and improving query performance.

## Data Analysis and Visualization

- **pandas:** pandas is a Python library used for data manipulation and analysis. It helps us clean, preprocess, and prepare the Twitter data for further analysis.

- **matplotlib and seaborn:** These Python libraries are employed for data visualization. We create insightful charts, graphs, and visualizations to present our findings effectively.

## Similarity Search using Locality-Sensitive Hashing (LSH)

- **Locality-Sensitive Hashing (LSH):** LSH is a technique used for approximate similarity search in high-dimensional spaces. In our project, LSH assists in identifying tweets or topics with similar content, allowing us to group related discussions and trends.

# Project Objectives

Our primary objectives in this project are as follows:

1. **Identify Emerging Education Trends:** Determine whether Twitter activity exhibits spikes or significant shifts in geographical distribution related to education topics, such as the example topic "Florida math book ban."

2. **Assess Credibility:** Evaluate whether the Twitter users discussing K-12 or Higher Education topics primarily consist of government institutions, universities, credible non-profit organizations, or random users discussing various aspects of education.

3. **Analyze Content Originality:** Investigate whether the majority of tweets represent original content or are merely retweets and copies of the original messages.

# Methodology

To achieve these objectives, we will follow a structured analysis process:

1. **Data Collection:** We will combine individual JSON files from Google Cloud Storage to create a comprehensive dataset of ~100 million Tweets.

2. **Trend Analysis:** We will use data analysis techniques to identify spikes in Twitter activity and shifts in the geographical distribution of Twitterers for education-related topics. This will help us determine if higher tweet volumes are indicative of emerging trends in education.

3. **User Classification:** We will categorize Twitter users into different groups, such as government institutions, universities, credible non-profits, and general users. This classification will provide insights into who is contributing to the education discourse on Twitter.

4. **Originality Assessment:** We will analyze the content of tweets to distinguish between original messages and retweets. This will help us understand the extent to which information is being disseminated on the platform.

# Conclusion

By harnessing the power of GCP, Big Data processing with Spark, and advanced techniques like LSH, we aim to provide valuable insights into the Twitter education discourse. Through data analysis and visualization, we can present our findings effectively, contributing to a better understanding of the role of Twitter in education trend identification and information dissemination.
