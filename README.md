# librenms_systemd_timers
Replacement of crontab entries for systemd timers.

To install:
move to /etc/systemd/system and run

# systemctl daemon-reload
# systemctl enable --now librenms-daily.timer
# systemctl enable --now librenms-every5mins.timer
# systemctl enable --now librenms-every6thhr.timer
# systemctl enable --now librenms-everyhour.timer
# systemctl enable --now librenms-everymin.timer
# systemctl enable --now librenms-everyquarter.timer


Based on https://gist.github.com/mikaelz/43689d5de272dc99df8d757d85246749
