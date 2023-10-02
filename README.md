# sql-splitter
This Python script is designed to help break down a large SQL file into smaller, more manageable chunks.

This script is designed to take a large SQL file and split it into smaller chunks. This is particularly useful when dealing with extensive SQL dumps or backups that need to be processed in parts, either for performance reasons or due to constraints in the environment where the SQL is being executed. The script reads the entire content of the input SQL file, splits it based on semicolons (assuming each SQL statement ends with a semicolon), and then writes the statements into separate chunk files.
Use Cases:

    Database Migration:
        Scenario: A company is migrating its database from one platform to another. The SQL dump from the old database is extensive, and the new platform has a size limit on the SQL files it can process at once.
        Solution: Use the script to split the large SQL dump into smaller chunks. Then, each chunk can be imported separately into the new platform, ensuring that the size constraints are met and the migration process is smooth.

    Performance Optimization:
        Scenario: A developer is working with a massive SQL file containing multiple statements. When trying to execute the entire file, it's causing performance issues, timeouts, or memory constraints in the database environment.
        Solution: By splitting the SQL file into smaller chunks using the script, the developer can execute each chunk sequentially. This approach reduces the load on the database at any given time and can help in avoiding timeouts or performance bottlenecks.
