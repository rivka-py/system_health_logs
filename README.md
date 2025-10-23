# System Health Logs

Bash script to monitor system health:
- Disk usage
- Active processes
- Logs results with timestamps
- Automated via cron

## Installation
Clone the repository to your local machine:
```bash
git clone git@github.com:RivkaRom/system_health_logs.git
```

## Usage
Run the script manually:
`./system_health.sh`

To run it automatically every hour using cron, add the following line to your crontab:

0 * * * * /home/rivka/project/system_health_logs/system_health.sh

## File Structure
`system_health.sh` — main Bash script

`log` — directory where logs are stored

## Author
Rivka Rom
