# mbiodb-site-usage
Analysis of MicrobiomeDB.org usage


This repo can be used to generate figures that show particular usage statistics for the MicrobiomeDB.org website. 

![Usage of curated studies over time](./images/HMP_analyses.svg)



## Getting started
### Specify environment variables
Ensure the following variables are specified in a `.env` file. For convenience, copy the `.env.sample` file to `.env` and update the values.

<!-- Table of variables -->
| Variable | Description |
|----------|-------------|
| DB_USER     | database user name |
| DB_PASSWORD     | database password |
| HOST     | host, example "localhost" |
| PORT     | port |
| DATABASE     | Database name |
| REMOVE_IDS     | User IDs that should be removed from the analysis. For example, exclude staff. |


### SSH to server
If necessary, ssh into the server on which your database resides

### Run the notebook
As long as the variables are specified correctly in `.env`, running the jupyter notebook should be hassle-free. Note that SQL queries are MicrobiomeDB-specific.

