# Projects by Omni Oracle

As part of a Data Engineering bootcamp, our team has done two projects to get hands-on experience in building an ETL pipeline to derive insights on the data we collected. 
The projects are done within 3 weeks using the skills and knowledge we get from DataCamp which is a self-directed learning platform and the guidance of our lecturer, Christine.

## IMDb Movies Data Pipeline

![imdb_top_250|100](https://syafaatsaat.github.io/portfolio/assets/images/imdb_top_250.jpg)

This was the first project done during the bootcamp. We were assigned to explore or source for the data, build a data crawler, clean the extracted data, store the crawled data in a Database Management System (DBMS), and ultimately, build an ETL data pipeline.

We based our data on the top 250 movies listed on the IMDb website (https://www.imdb.com/chart/top/?ref_=nv_mv_250) and sourced out more data from the OMDb (https://www.omdbapi.com/) and TMDB (https://www.themoviedb.org/) websites. The data is transformed using Python and some open-source libraries in Jupyter Notebook. Lastly, we stored the data in PostgreSQL where we designed the database schema, tables and entity-relationship models.

### Development Stages
1. Web Crawler to scrape data from IMDb website
2. API requests from OMDb and TMDB
3. Data Transformation
4. Loading data into PostgreSQL using SQLAlchemy
5. Make queries to learn about the data

## Olist Store (Brazilian E-Commerce) Data Pipeline

![olist|100](https://syafaatsaat.github.io/portfolio/assets/images/olist.jpg)

This was the second project done during the bootcamp. We were assigned to formulate an architecture solution in creating an ETL/ELT pipeline to ingest a dataset and carry out data analysis to provide strategic recommendations on a business intelligence dashboard using Power BI. For this project, we tried to explore the Azure cloud services provided by Microsoft to create the architecture solution. 

The data that we are working with is the Olist Store which is a Brazilian online marketplace, which is sourced from the Kaggle website (https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

### Development Stages
1. Store data inside local PostgreSQL database
2. 
