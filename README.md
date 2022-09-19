# Query a Digital Music Store Database (SQLite)

## <b>Introduction</b><br>

In this project, I am querying the [Chinook Database](https://github.com/lerocha/chinook-database) which holds information about a music store. The goal is to assist the Chinook team with understanding the media in their store, their customers and employees, and their invoice information. 

## <b>The Chinook Database</b><br>

As a reference for the database & queries, the schema for the Chinook Database is provided below. There we can see the columns that link tables together via the arrows. This diagram is known as an <b>entity-relationship diagram (ERD)</b>, shows us how data is structured in the database and helps us visualize the data we are analyzing.

![Chinook Database Schema](https://github.com/dimikara/SQL-Query-a-DB/blob/main/chinook_db_schema.png)

The Chinook Database contains the following tables:

| Table | Content |
| :---: | :---: |
| `Album` | List of tracks and Artist ID |
| `Artist` | Artist ID and name |
| `Customer` | Customer data |
| `Employee` | Employee data |
| `Genre` | Music genre, for example, rock, blues, latin, etc. |
| `Invoice` | Invoice data |
| `Invoiceline` | Invoice item data per line |
| `MediaType` | For example, MPEG or Protected AAC audio file |
| `Playlist` | Playlist ID & name |
| `PlaylistTrack` | Playlist & Track IDs |
| `Track` | Song data |



## <b>Used Skills</b><br>

The main goal of this project is to use SQL for querying the Chinook database. For the execution of SQL queries I am using [DB Browser for SQLite](https://sqlitebrowser.org/dl/).



## <b>Project</b><br>

The project consists of the following:<br>

* Writing 4 SQL queries in order to reply to 4 business questions

* Extracting the data to Excel and create an appropriate visualization for each of the questions

* Creating a [Presentation](https://github.com/dimikara/SQL-Query-a-DB/blob/main/Presentation.pdf) file to share the findings. This file contains 5 slides for the business questions I am querying the database about.



## Business questions

* 1. How is Revenue split per Media Type?

* 2. Which is the Music Genre that dominates in most countries?

* 3. Which are the top 10 Artists that earned the most on 2013?

* 4. How did the Revenue for “Rock” genre change during the period 2009-2013?



## <b>How to run the queries</b><br>

To run the queries yourself, follow the instructions below:

1. Download the Chinook database from the [GitHub](https://github.com/lerocha/chinook-database) site<br>

2. Download the appropriate version of [DB Browser for SQLite](https://sqlitebrowser.org/dl/), depending on your computer setup<br>

3. Connect the Browser to the Database, following the below steps:<br>
    - Open up _DB Browser for SQLite_
    - Click on _Open Database_
    - Navigate to the _Chinook.db_ file in the folder where you saved it
    - Click on the _Execute SQL_
    - Copy and paste the queries from the [txt file]() or write your own queries to query the data

![SQLite browser](https://github.com/dimikara/SQL-Query-a-DB/blob/main/SQLite_browser.JPG)


_Notes:_

* Although here I am using the DB Browser for SQLite, there are many different SQL database browsers that can work with different types of databases.
* All graphs were created in Google Sheets.

## References

* [Chinook Database](https://github.com/lerocha/chinook-database)
* [DB Browser for SQLite](https://sqlitebrowser.org/dl/)
* [Online SQL fortmatting service](https://sqlformat.org/)

__________________________________________
