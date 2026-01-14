# log analysis project 
Analyzed Linux authentication logs (/var/log/auth.log) to identify failed login attempts and check for brute-force behavior using grep, awk, sort, and uniq. Created a structured report with findings, screenshots, and documented command usage. Suitable as a beginner SOC Analyst project.


# Log Analysis 

Objective:
Analyze Linux authentication logs to detect failed logins and brute-force attempts.

Log Source:
/var/log/auth.log

Steps:
1. Viewed log file using cat and less
2. Searched failed login attempts using grep
3. Extracted fields using awk
4. Counted repeated patterns using sort and uniq
5. Analyzed results

Tools:
 grep, awk, sort, uniq  

Result:
No major brute-force activity detected. Logs mainly contained sudo command records.


