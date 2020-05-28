# Scheduling_files
Scheduling Files to read, perform transformations and saving it to MariaDB.

### First Commit :
WatchDog - To keep track of the given Directory. Whenever a new file is added the code starts executing.
"pip3 install watchdog"

MariaDB - Mysql-connector used to connect python to the database.
"pip3 install mysql-connector-python"



#### To check if the file is fully uploaded:
file_size = -1
    while file_size != os.path.getsize(event.src_path):
        file_size = os.path.getsize(event.src_path)
        time.sleep(1)
