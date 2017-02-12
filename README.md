# Reboot Notifier

Reboot Notifier is a small bash script that emails you if your Debian based host needs restarting after package updates.

## Installation

The easiest way to install and run Reboot Notifier is to just drop it into `/etc/cron.daily` so it automatically executes every day.

```bash
curl -so /etc/cron.daily/reboot-notifier https://raw.githubusercontent.com/jloh/reboot-notifier/master/reboot-notifier
chmod +x /etc/cron.daily/reboot-notifier
```