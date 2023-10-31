# steamdeck-bedtime

1. **via Desktop mode**:
   - Copy "bedtime.service" and "bedtime.timer" to `/home/deck/.config/systemd/user/`.

2. **Enable the timer**:
   - Run the following command:
     ```shell
     systemctl enable --user --now bedtime.timer
     ```
