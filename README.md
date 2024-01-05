# steamdeck-bedtime

1. **via Desktop mode**:
   - Copy "asksudo.sh", "bedtime.service" and "bedtime.timer" to `/home/deck/.config/systemd/user/`.
   - update asksudo.sh with the current deck user password

2. **Terminal updates**:
   - Open the Konsole app from desktop mode
   -    - Run the following commands:
     ```shell
     chmod 0700 /home/deck/.config/systemd/user/asksudo.sh
     systemctl enable --user --now bedtime.timer
     ```
