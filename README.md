# ARCHIVING AND LOGGING DATA LAB

## Objective

The Archiving and Logging Data Lab was aimed to understand archiving, logging, auditing, backups, scripting, task automation, and contribute to a comprehensive log management system. The primary focus was expand and enhance the log management system by using new tools, adding new advanced features, researching additional concepts, and understand the Fereral Trade Commission's Gramm-Leach-Biliey Act (GLBA).

### Skills Learned

- Understanding Log size management.
- Understanding Log auditing.
- Performing Log filtering.
- Managing backups using cron jobs.
- Writing bash scripts to create system resource usage reports.

### Tools Used

- auditd to track event, record the events, detect unauthorized activity, and create reports.
- logrotate used to contain log size management.
- Journalctl for log filtering.
- Cron jobs for managing backups.
- Bash scripts to create system resource reports.
- Tar command to archive data.
- Crontab.guru for making cron jobs.


## Steps

1. Creating, extracting, compressing, and managing tar backup archives

Downloading a TarDocs.tar to extract the contents and within I get new subdirectories. Within those I wantt to make a tar archive that excludes a directory from the extracted directory and verify the the contents after.


2. Creating, managing, automating cron jobs

Creating a cron job with crontab.guru to schedule the archiving process.

3. Writing bash scripts

Creating a script to print free memory, disk usage, lists all open files, and file system disk space statistics and stores them in their backup folders.

4. Managing log file sizes

implementing log rotation in order to preserve log entries and keep log files more manageable and compress logs to preserve disk space.

5. Checking for policy and file vioations

Creating a event montioring system that generates reports when new accounts are created or modified.

6. Performing various log filtering techniques

filtering through log files to determine if there are any threats.   
