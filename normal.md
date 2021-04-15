# DATABASE normalization
### Database normalization is a process used to organize a database into tables and columns.
The main idea with this is that a table should be about a **specific topic** and **only** supporting topics included.This eliminates some issues stemming from database modifications.

-----

## There are three normal forms most databases adhere to use:
1. ## First normal form: The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.
2. ## Second normal form: The table is in first normal form and all the columns depend on the table’s primary key.
3. ## Third normal form: the table is in second normal form and all of its columns are not transitively dependent on the primary key

-----

## Reasons for DB normalization:
* To minimize duplicate data
* To minimize or avoid data modification issues
*  To simplify queries

-----

### Data Duplication and Modification Anomalies:
* Insert Anomaly
* Update Anomaly
* Deletion Anomaly