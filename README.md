# Formula1-Waterfall-to-Star
The database provided is a relational database, but it's not a star schema, which is necessary in PowerBI as it causes ambiguity.
The first step is to create a new database cloning the f1db, done by backing up the db and then restoring it on a new one called f1db_star
Then, I'll be using a Results_fact table which is a Union between the results and sprint_results tables - see 
