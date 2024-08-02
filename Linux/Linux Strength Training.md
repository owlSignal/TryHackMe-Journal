# Notes During the Room:

1. Finding files and directories:
   - Use the `find` command with various options
   - Can search based on filename, size, user/group, date modified/accessed, and content

2. File and folder operations:
   - Copy: `cp`
   - Move: `mv`
   - Rename: `mv`
   - Create file: `touch`
   - Create folder: `mkdir`
   - Edit file: `nano`
   - Output file contents: `cat`

3. Hashing:
   - One-way function to create a unique representation of data
   - Used for integrity checking and password storage
   - Common algorithms: MD5, SHA1, SHA-256
   - Can be cracked using tools like John the Ripper

4. Base64:
   - Binary-to-text encoding scheme
   - Used for data representation in some systems
   - Can encode/decode using `base64` command

5. Encryption/Decryption:
   - Process of concealing sensitive data
   - Uses a key for reversing the process
   - Common tool: `gpg`
   - Can be cracked using John the Ripper with `gpg2john`

6. SQL:
   - Language for managing databases
   - Basic commands:
     - Start/stop MySQL: `service mysql start/stop`
     - Connect to remote database: `mysql -u [username] -p -h [host ip]`
     - Open local database: `mysql`
     - Show databases: `SHOW DATABASES;`
     - Select database: `USE [database name];`
     - Show tables: `SHOW TABLES;`
     - Describe table: `DESCRIBE [table name];`
     - Display data: `SELECT * FROM [table name];`

# Important Takeaways:

1. The `find` command is versatile for locating files and directories based on various criteria.
2. Basic file operations are essential for managing the filesystem.
3. Hashing is crucial for data integrity and secure password storage.
4. Base64 encoding is useful for data representation in certain systems.
5. Encryption protects sensitive data, but can be cracked with the right tools.
6. Understanding basic SQL commands is important for database management and data retrieval.
