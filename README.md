Level 100

1. **Time Announcer:** 
  Write a script that displays a personalized greeting along with the current time every minute. For example, "Good morning, Alice! It's Wednesday, 27 March 2024 11:15 AM." (Use `date` and a loop to update every minute).

2. **System Uptime Monitor:** 
  Write a script that displays the system uptime and refreshes it every 5 seconds. Use the `uptime` command and a loop to achieve real-time updating.

3. **Interactive File Size Check:** 
  Write a script that prompts the user for a file path and displays the file size in real-time as the user types (using backspace for corrections). Employ the `read` command and the `du -s` command to check size.

4. **Countdown with User Input:** 
  Write a script that asks the user for a duration in seconds and displays a countdown timer that updates every second until it reaches zero. Combine a loop with the `sleep` command for real-time updates.

5. **Interactive Currency Converter:** 
  Write a script that prompts the user for an amount in their local currency and displays the equivalent value in another currency. Use a loop for continuous input and consider APIs for real-time conversion rates (may require additional research).

6. **Simple File Change Monitor:** 
  Write a script that monitors a specific file for changes. If the file modification time changes, the script displays a message indicating the file has been modified. Use the `stat` command for comparisons.

7. **Real-Time Fortune Teller (Simple):** 
  Write a script that displays a random fortune message. Use a loop and pre-defined fortunes stored in an array for real-time display.

8. **Simple System Info Display:** 
  Write a script that displays essential system information like the current user, hostname, and operating system version in real-time. Update the script to display this information periodically (e.g., every minute). (Use commands like `whoami`, `hostname`, and `uname -r` to retrieve the information).

9. **Free Disk Space Monitor:** 
  Write a script that checks the free disk space on a specific partition  (e.g., `/`) and displays the available space in megabytes (MB) or gigabytes (GB). Update the information periodically (e.g., every minute) using a loop.

10. **Simple File Watcher:** 
  Write a script that monitors a specific file for changes (modifications). Use a loop to check the file's last modified time and display a message if it has been updated since the script started.

11. Network Health Monitoring Tool**
  Objective: Create a script that checks the network health of your server. It should ping a set of predefined IPs or domain names and report any failures along with the timestamp. The script should log this information and send an alert (e.g., via email) if any of the pings fail.

12. **Log File Analyzer**
  Develop a script that analyzes a specified log file (e.g., Apache or Nginx access log) and extracts information such as the most frequent IP addresses and request URLs. The script should also identify any error codes (like 404 or 500) and count their occurrences.

13. **User Account and Permission Audit Script**
  Objective: Create a script that audits user accounts and file permissions in a system. The script should list all users, their last login time, and check for any files in sensitive directories (like /etc or /var) with permissions that are too permissive (e.g., world-writable files).

Level 200 - 300

1. **Interactive System Resource Monitor (Graphical):** 
  Write a script that monitors CPU, memory, and network usage. Utilize libraries like `ncurses` to display them in a user-configurable graphical format (e.g., bar charts, gauges). Allow users to choose the refresh rate and potentially switch between different display modes.

2. **Service Monitoring Script**: 
  Develop a script that monitors critical system services (e.g., Apache, SSH, MySQL) and restarts them automatically if they are found to be down. Include logging functionality to record service status changes.

3. **User Account Management Tool**: 
  Build a shell script for managing user accounts on a Linux system. The script should allow administrators to add, modify, and delete user accounts, set password policies, and manage user permissions.

4. **File Encryption/Decryption Tool**: 
  Develop a shell script that encrypts and decrypts files using symmetric encryption algorithms (e.g., AES). Ensure that the script prompts the user for a passphrase and supports options for both encryption and decryption.

5. **Database Backup and Restore**: 
  Develop a shell script that automates the backup and restore process for databases such as MySQL or PostgreSQL. The script should dump the database contents, compress them, and store them securely. It should also be able to restore databases from backup files.

## Cron Job Assignment
1. **Traffic Monitoring:**
    - Task: Run a script every 5 minutes to collect network traffic statistics. If the incoming traffic exceeds a certain threshold for three consecutive checks, send an email alert to the network administrator.
    - Focus: Scripting logic, conditional cron execution, persistence for traffic tracking.
2. **Emailing System Logs:**
    - Task: Set up a cron job to compress system logs daily at 2:30 AM, delete compressed log files older than 30 days, and email a report of successful and failed compressions to the system administrator.
    - Focus: File manipulation, error handling, email integration
