Common-Data-Model / SQL Server
=================

This folder contains the SQL scripts for SQL Server. 

In order to create your instantiation of the Common Data Model, we recommend following these steps:

1. Create an empty schema.

2. Execute the script `OMOP CDM sql server v5_3_1 ddl.sql` to create the tables and fields.

3. Execute the script `OMOP CDM sql server v5_3_1 primary keys.sql` to add the primary key constraints.

4. Load your data into the schema.

5. Execute the script `OMOP CDM sql server v5_3_1 indices.sql` to add the minimum set of indices we recommend.

6. Execute the script `OMOP CDM sql server v5_3_1 constraints.sql` to add the foreign key constraints.

Note: you could also apply the constraints and/or the indexes before loading the data, but this will slow down the insertion of the data considerably.
