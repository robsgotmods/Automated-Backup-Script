How to Use
Set the Source and Backup Directories: Replace "/path/to/source_directory" and "/path/to/backup_directory" with the actual paths of the directories you want to back up and where you want to store the backups.

Run the Script Manually: You can run the script manually to test it by using the command:

bash
Copy code
python backup_script.py
Schedule the Script Using Cron Jobs:

Open your crontab file by running:
bash
Copy code
crontab -e
Add a line to schedule the script. For example, to run the script daily at 2 AM, add:
bash
Copy code
0 2 * * * /usr/bin/python3 /path/to/backup_script.py
