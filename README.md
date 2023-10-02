# sql-splitter
This Python script is designed to help break down a large SQL file into smaller, more manageable chunks. Use the script to split the large SQL dump into smaller SQL chunks.

This script is designed to take a large SQL file and split it into smaller chunks. This is particularly useful when dealing with extensive SQL dumps or backups that need to be processed in parts, either for performance reasons or due to constraints in the environment where the SQL is being executed. The script reads the entire content of the input SQL file, splits it based on semicolons (assuming each SQL statement ends with a semicolon), and then writes the statements into separate chunk files.



