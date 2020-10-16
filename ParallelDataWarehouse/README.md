Common-Data-Model / Parallel Data Warehouse
=================

This folder contains the script for Parallel Data Warehouse. 

n order to create your instantiation of the Common Data Model, we recommend following these steps:

1. Create an empty schema.

2. Execute the script `OMOP CDM pdw v5_3_1 ddl.sql` to create the tables and fields.

3. Load your data into the schema.

4. Execute the script `OMOP CDM pdw v5_3_1 indices.sql` to add the minimum set of indices we recommend.

5. Execute the script `OMOP CDM pdw v5_3_1 constraints.sql` to add the foreign key constraints.
