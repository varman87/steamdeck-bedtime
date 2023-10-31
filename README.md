# steamdeck-bedtime

via Desktop mode
copy bedtime.service and bedtime.timer to /home/deck/.config/systemd/user/
Enable the timer. 
  systemctl enable --user --now bedtime.timer
