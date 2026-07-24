# Question 1 Explanation

- `chmod +x setup_test.sh && ./setup_test.sh`: This made the setup script executable and generated sample submission files for testing duplicate detection.
- `ls -la submissions/ && md5sum submissions/*`: This listed the files and calculated checksums to confirm which submissions had identical contents.
- `chmod +x solution.sh && ./solution.sh`: This ran the main solution script to detect duplicates, back up unique files, and produce the report and error log.
- `cat report.txt`: This displayed the generated summary to verify the number of files processed, duplicates found, and backups created.
- `cat errors.log`: This checked the separate error log to confirm the run completed without errors.
