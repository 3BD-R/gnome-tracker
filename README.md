# gnome-tracker
### disable
- `systemctl --user mask tracker-store.service tracker-miner-fs.service tracker-miner-rss.service tracker-extract.service tracker-miner-apps.service tracker-writeback.service`
- then reset tracker `tracker reset --hard`
- reboot

### enable
- `systemctl --user unmask tracker-store.service tracker-miner-fs.service tracker-miner-rss.service tracker-extract.service tracker-miner-apps.service tracker-writeback.service` then reboot
