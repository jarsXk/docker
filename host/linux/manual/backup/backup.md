## btrfs linux host
```
apt install fsarchiver parted
wget \
  --header 'Accept: application/vnd.github.v3.raw' \
  -O /usr/local/sbin/backup-btrfs.sh \
  https://api.github.com/repos/jarsXk/homelab/contents/host/linux/manual/backup/backup-btrfs.sh
chmod ug+x /usr/local/sbin/backup-btrfs.sh
micro /usr/local/sbin/backup-btrfs.sh
wget \
  --header 'Accept: application/vnd.github.v3.raw' \
  -O /etc/cron.d/backup-btrfs \
  https://api.github.com/repos/jarsXk/homelab/contents/host/linux/manual/backup/backup-btrfs

```
