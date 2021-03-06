# Airbnb - Paris
## Getting Started
1. Install Python modules
```
pip install -r requirements.txt
```

2. Create a `dev.env` file in the **root folder** with the following content:
```
POSTGRESQL_HOST=
POSTGRESQL_USER=
POSTGRESQL_PASSWORD=
POSTGRESQL_DATABASE=
```

To access and visualize the database, you can use [pgAdmin](https://www.pgadmin.org/download/).

## Organization of Files and Folders

- **datasets**: Regroup all datasets files
  - **datasets/listing**: Regroup listings datasets
  - **datasets/review**: Regroup reviews datasets
  - **datasets/calendar**: Regroup calendars datasets
- **mysql**: Regroup all database files
  - **mysql/aribnb**: Volume from docker airbnb's database
- **tests**: All the tests files that you have
