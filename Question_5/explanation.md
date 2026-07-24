# Question 5 Explanation

- `vi config.cfg`: This opened the configuration file in vi so the interrupted edit could be reviewed.
- `vi` swap recovery prompt: Vi detected the swap file after the crash and offered recovery of the unsaved work.
- `:wq` or saving the recovered content: Saving the recovered file preserved the latest changes and prevented data loss.
- `cp config.cfg config.cfg.bak`: This created a backup copy of the recovered file to protect the restored content.

The most reliable recovery strategy is to recover from the swap file first, then save the recovered content to a backup copy and compare it with the original file to confirm the result.
