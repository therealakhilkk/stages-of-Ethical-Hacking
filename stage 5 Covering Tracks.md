Covering Tracks (Clearing Evidence) 
After gaining and maintaining access, ethical hackers simulate how attackers cover their tracks to avoid detection. 
This step involves deleting logs, modifying timestamps, and hiding malicious processes to ensure stealth.
Covering tracks should be performed responsibly in authorized penetration testing scenarios, ensuring organizations learn how to detect and mitigate such activities.

Techniques for Covering Tracks
Clearing System Logs
Attackers erase or modify logs to remove traces of their activity.

Linux: /var/log/auth.log, /var/log/syslog
Windows: Event Viewer -> Windows Logs

Disabling Logging Services
Prevents logs from being written in real-time.

Editing Timestamps (Timestomping)
Modifies file timestamps to prevent forensic detection

Hiding Processes & Files
Attackers use rootkits and hidden directories to evade detection.

Deleting Command History
Removes executed command traces from history files.

 Removing Malware & Backdoors
 Attackers delete their payloads after execution to minimize detection.
 
