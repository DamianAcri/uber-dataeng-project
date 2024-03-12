# uber-dataeng-project
Uber Data Engineering Project

The goal of this project is to perform data analytics on Uber data using various tools and technologies, including GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio.

## 1. Data Acquisition and Cleaning:
Data Acquisition: I acquired the uber_data.csv file containing a wealth of information about Uber trips.
Data Cleaning: Recognizing the importance of data quality, I implemented rigorous cleaning techniques to meticulously rectify any errors or inconsistencies present within the dataset. This included addressing missing values, formatting inconsistencies, and correcting outliers.

## 2. DataFrame Design and Development:
Conceptualization of DataFrames (DFs): I designed multiple DFs to efficiently organize and structure the diverse information contained within the uber_data.csv file.
Implementation in Jupyter Lab: Using Python, I wrote scripts within Jupyter Lab to generate and populate these DFs. These ensured data manipulation accuracy and facilitated further analysis.

## 3. Data Transformation and Loading in Google Cloud:
Data Transformation: To integrate with the BigQuery schema, the data underwent some transformations. 
Leveraging Google Cloud: I used Google Cloud to manage the data loading process.
Debian 11 Virtual Machine: I set up a dedicated Debian 11 virtual machine within Google Cloud to provide a robust environment for executing data pipelines using Mage AI.
Mage AI Pipelines: Design and implementation pipelines using Mage AI. These pipelines facilitated efficient data uploading, transformation, and subsequent export to BigQuery via its API.

## 4. Data Analysis with BigQuery and Looker Studio:
Building the BigQuery Table: I crafted a new table within BigQuery to house the essential data extracted from the Uber trip records. This table served as the foundation for in-depth analysis.
Interactive Data Visualizations with Looker Studio: I utilized Looker Studio to construct interactive data visualizations that brought the data to life. These visualizations allowed me to explore trends and patterns.

## 5. Acknowledgments: 
Darshil Parmar, for all the info provided.
