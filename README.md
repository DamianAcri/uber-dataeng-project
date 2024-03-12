# uber-dataeng-project
Uber Data Engineering Project

This comprehensive data engineering project unveils valuable insights from official Uber trip data provided in CSV format. I embarked on a journey through the following stages:

1. Data Acquisition and Cleaning:
Data Acquisition: I acquired the uber_data.csv file containing a wealth of information about Uber trips.
Data Cleaning: Recognizing the importance of data quality, I implemented rigorous cleaning techniques to meticulously rectify any errors or inconsistencies present within the dataset. This included addressing missing values, formatting inconsistencies, and correcting outliers.

2. DataFrame Design and Development:
Conceptualization of DataFrames (DFs): I designed multiple DFs to efficiently organize and structure the diverse information contained within the uber_data.csv file.
Implementation in Jupyter Lab: Leveraging the power of Python, I crafted scripts within Jupyter Lab to generate and populate these DFs. My scripts ensured data manipulation accuracy and facilitated further analysis.

3. Data Transformation and Loading in Google Cloud:
Data Transformation: To seamlessly integrate with the BigQuery schema, the data underwent meticulous transformations. This might have involved tasks like data type conversions, feature engineering, and date/time formatting adjustments.
Leveraging Google Cloud: I harnessed the power of Google Cloud to seamlessly manage the data transformation process.
Debian 11 Virtual Machine: I set up a dedicated Debian 11 virtual machine within Google Cloud to provide a robust environment for executing data pipelines using Mage AI.
Mage AI Pipelines: I meticulously designed and implemented pipelines using Mage AI. These pipelines facilitated efficient data uploading, transformation, and subsequent export to BigQuery via its API.

4. Data Analysis with BigQuery and Looker Studio:
Building the BigQuery Table: I crafted a new table within BigQuery to house the essential data extracted from the Uber trip records. This table served as the foundation for in-depth analysis.
Interactive Data Visualizations with Looker Studio: I utilized the intuitive features of Looker Studio to construct interactive data visualizations that brought the data to life. These visualizations allowed me to explore trends and patterns in an engaging and informative way.
Key Findings:
Interactive Dashboards: Developing interactive dashboards within Looker Studio would enhance data visualization experiences and enable users to explore the data in a more self-directed and insightful way.
Data Integration: Integrating Uber data with complementary sources, such as public transportation data or city demographics, could provide a more comprehensive perspective on urban dynamics and travel behavior.

5. Acknowledgments: Darshil Parmar
