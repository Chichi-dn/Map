sqoop import \
--connect jdbc:mysql://your_database_host/your_database_name \
--username your_username \
--password your_password \
--table your_table_name \
--hive-import \
--hive-database your_hive_database \
--hive-table your_hive_table \
--create-hive-table \
--target-dir /user/hive/warehouse/your_hive_database.db/your_hive_table
