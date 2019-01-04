# website_blocker
blocks selected websites during business hours

run as cron on Mac:
crontab -e
@reboot /path/to/python3 /path/to/script/website_blocker.py

if getting editor errors:
export EDITOR="nano"
export VISUAL="nano"
