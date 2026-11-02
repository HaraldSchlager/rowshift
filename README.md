# RowShift
RowShift is a Java command-line tool that moves table data between relational databases over JDBC. It copies single tables or whole groups of tables, checks the result with row counts and sample comparisons, runs SQL scripts against a database, and translates DB2 SQL into Oracle SQL. It was written for migrating DB2 (including DB2 for z/OS) to Oracle and also works with PostgreSQL and SQLite. Every run is recorded in a local SQLite database, so long migrations can be tracked, resumed and audited.

Further informations about the status of the project can be found at https://rowshift.at/de/solutions/rowshift
