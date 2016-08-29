# CronJob-Script
# m h  dom mon dow   command
*/5 10-18 * * * /home/arun/test.sh >> /home/arun/Slogs/Logsbackup_ output.txt 2>&1 <br/>
*/10 10-18 * * * /home/arun/arun.sh > /home/arun/Alogs/Logsbackup_ output.txt 2>&1 <br/>
*/30 10-18 * * * /home/arun/arun.sh >> /home/arun/Dlogs/Logsbackup_ output.txt 2>&1 .
