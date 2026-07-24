# Question 4 Explanation

- `chmod +x simulate_logs.sh && ./simulate_logs.sh`: This generated sample server log entries with different severity levels for monitoring practice.
- `./monitor.sh`: This ran the monitoring workflow to display logs, extract errors, and save them into a separate report file.
- `cat error_report.txt`: This verified that the report contained only the ERROR messages.
- `echo "Total: $(wc -l < server.log) | Errors: $(wc -l < error_report.txt)"`: This compared the total log count with the extracted error count to confirm filtering worked.
- `tail -f server.log`: This demonstrated real-time log monitoring, where new lines appear as they are written.
- `ls nonexistent 2>/dev/null; echo "stderr suppressed"`: This showed how `/dev/null` hides unnecessary error output from the terminal.
