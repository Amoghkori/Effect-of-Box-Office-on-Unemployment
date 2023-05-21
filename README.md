# Data Preparation and Cleaning for Movie Ratings and US Unemployment Rate Datasets

This project report discusses the data preparation process for two datasets: movie ratings and reviews, and the US unemployment rate. The data underwent an 8-step data wrangling process to create an Analytic Base Table (ABT) structure. The process included steps such as discovery, structuring, cleaning, validating, enrichment, aggregation, integration, and publishing.

The primary goal of the data preparation process was to ensure that as much of the entire dataset as possible was ready for analysis. By removing extraneous variables at the end of the process, the report suggests that additional variables could be available for analysis in case the scope of the analysis expanded later on.

Data structuring techniques played a crucial role in normalizing the data and reducing complexity. The report ensured that each variable contained an atomic value, and incorrect datatype assignments were corrected through datatype conversions. Furthermore, some schema conversions were performed to transform JSON formatted strings into a tabular format, improving the dataset's usability.

Data cleaning was a vital step to ensure the accuracy and reliability of the analysis. Outliers were removed from the datasets, such as movies with a revenue value of 0. Movies that were released straight to video or had a status other than RELEASED were also dropped from consideration. Entries with missing values for essential fields, like the release date, were excluded to maintain data integrity.

In summary, the report underscores the significance of data preparation and cleaning in guaranteeing accurate and reliable analysis. The 8-step data wrangling process employed in this project provides a valuable framework for preparing and cleaning data. The report emphasizes the importance of data structuring techniques to normalize data and reduce complexity, as well as the necessity of data cleaning to eliminate outliers and missing values.

Please note that this is a summary of the project and further details can be found in the complete report.
