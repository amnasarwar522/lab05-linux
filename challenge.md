## Question 1
Answer: I am logged in as amnasarwar522. My home folder is /home/amnasarwar522.
Commands: whoami, pwd

## Question 2
Answer: The server name is ubuntu. It runs Ubuntu 26.04.1 LTS.
Commands: hostname, cat /etc/os-release | head -2

## Question 3
Answer: The server has 1.6Gi of RAM in total. The disk is 9.8G in size and 2.7G is free.
Commands: free -h, df -h /

## Question 4
Answer: Two users can log in with /bin/bash: root and amnasarwar522.
Commands: grep bash /etc/passwd

## Question 5
Answer: ps aux prints 252 lines, so about 251 processes are running (one line is the header).
Commands: ps aux | wc -l

## Question 6
Answer: lab5user was created at 2026-10-20T11:04:06.091438+00:00 and deleted at 2026-10-20T11:03:39.157025+00:00 (times are in UTC).
Commands: sudo grep lab5user /var/log/auth.log
