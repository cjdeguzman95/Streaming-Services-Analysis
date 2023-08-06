# Streaming Services Analysis
#### <i>Technologies: Python (Pandas), Microsoft Power BI</i>

This project demonstrates:
- Ingesting multiple datasets and transforming them into one consolidated masterfile (see code [here](https://github.com/cjdeguzman95/Streaming-Services-Analysis/blob/main/Streaming%20Services/Code/streaming-services-project-data-cleaning.ipynb))
- Creating a star schema data model using Python (see code [here](https://github.com/cjdeguzman95/Streaming-Services-Analysis/blob/main/Streaming%20Services/Code/streaming-services-project-data-modelling.ipynb))
- Creating a snowflake data model in Power Query
  - Additional tables were necessary for the data to be visualised correctly
  - The final data model behind the Power BI dashboard is the below
    ![image](https://github.com/cjdeguzman95/Streaming-Services-Analysis/assets/62239042/d6d01998-dbb5-475e-bf7f-470e5a5dd43b)
- Creating a Power BI dashboard (view dashboard [here](https://app.powerbi.com/view?r=eyJrIjoiZWY3NDhhN2UtOGM4MC00MTdiLWIzOTQtMDI1NDBhZTg2N2I0IiwidCI6ImY0NWRmN2YzLWY3ZTMtNDE4My1iZjhjLTIwZTcyM2Q1NDRlYyJ9&pageName=ReportSectionfe010c6384acc55b110a))

This project explores data from the top three streaming services (Netflix, Amazon Prime and Disney+)

The data is analysed to answer the following questions:
1. If any, what titles are unique to each streaming service?
2. What is the spread of titles across different viewing certifications?
3. Is there a clear leader in delivering a specific media type? (e.g. is Netflix really better for TV Shows compared to the rest?)

Sources: [Netflix Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows), [Amazon Prime Dataset](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows), [Disney+ Dataset](https://www.kaggle.com/datasets/shivamb/disney-movies-and-tv-shows)
