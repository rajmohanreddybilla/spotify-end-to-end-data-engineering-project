# ETL Pipeline for Spotify Data on AWS

### Description:

In this project, I developed a fully automated ETL (Extract, Transform, Load) pipeline using the Spotify API, leveraging AWS services to manage data efficiently and scale seamlessly. This pipeline performs the following operations:

1. **Extraction**: The pipeline uses the Spotify API to extract music-related data, including album details, artist profiles, and track information. The data is structured in JSON format, ensuring comprehensive data collection for further analysis.

2. **Transformation**: After extraction, the data is processed to ensure consistency and usability. I applied transformations such as data normalization, filtering, and restructuring to create clean datasets. Key transformations included parsing album release dates, formatting song duration, and linking track data with album and artist details.

3. **Loading**: The transformed data is loaded into AWS S3, providing a durable and highly available storage solution. The data is stored in a structured format, making it easily accessible for further analysis, visualization, or integration with data analytics services. Each dataset (albums, artists, songs) is loaded into separate folders in S3, maintaining organized data segregation.

This project enables efficient, real-time data collection from Spotify and can be used to track trends, perform analyses on music popularity, or integrate with machine learning workflows. AWS was chosen as the data store for its scalability, ease of integration with various AWS analytics tools, and cost-effectiveness.
