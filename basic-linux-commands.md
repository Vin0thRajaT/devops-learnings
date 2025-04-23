# Essential Linux & DevOps Command Cheat Sheet

## ls

- **Purpose:** List files with details

- **Example:** `ls -al`

## cd

- **Purpose:** Change directory

- **Example:** `cd /var/log`

## pwd

- **Purpose:** Print working directory

- **Example:** `pwd`

## cp

- **Purpose:** Copy files or directories

- **Example:** `cp source.txt dest.txt`

## mv

- **Purpose:** Move or rename files

- **Example:** `mv old.txt new.txt`

## rm

- **Purpose:** Remove files/directories

- **Example:** `rm -rf temp/`

## mkdir

- **Purpose:** Create directories

- **Example:** `mkdir -p backups/2025`

## touch

- **Purpose:** Create empty file or update timestamp

- **Example:** `touch new.log`

## cat

- **Purpose:** Concatenate & display file

- **Example:** `cat config.yaml`

## less

- **Purpose:** View file with paging

- **Example:** `less large.log`

## head

- **Purpose:** Show first lines

- **Example:** `head -n 20 access.log`

## tail

- **Purpose:** Show last lines / follow logs

- **Example:** `tail -f app.log`

## grep

- **Purpose:** Search text by pattern

- **Example:** `grep 'ERROR' app.log`

## awk

- **Purpose:** Pattern scanning & processing

- **Example:** `awk '{print $1}' data.csv`

## sed

- **Purpose:** Stream editor for find/replace

- **Example:** `sed -i 's/dev/prod/g' config.yaml`

## cut

- **Purpose:** Cut sections from lines

- **Example:** `cut -d':' -f1 /etc/passwd`

## sort

- **Purpose:** Sort lines

- **Example:** `sort numbers.txt`

## uniq

- **Purpose:** Filter duplicate lines

- **Example:** `sort items.txt | uniq -c`

## tr

- **Purpose:** Translate/delete characters

- **Example:** `echo 'ABC' | tr 'A-Z' 'a-z'`

## wc

- **Purpose:** Word/line count

- **Example:** `wc -l script.sh`

## find

- **Purpose:** Search files by criteria

- **Example:** `find . -type f -name '*.log'`

## locate

- **Purpose:** Fast file search

- **Example:** `locate nginx.conf`

## df

- **Purpose:** Disk space usage

- **Example:** `df -h`

## du

- **Purpose:** Disk usage of files/dirs

- **Example:** `du -sh *`

## free

- **Purpose:** Memory usage

- **Example:** `free -h`

## uptime

- **Purpose:** System load & uptime

- **Example:** `uptime`

## top

- **Purpose:** Interactive process viewer

- **Example:** `top`

## htop

- **Purpose:** Improved process viewer

- **Example:** `htop`

## ps

- **Purpose:** Process status

- **Example:** `ps aux | grep nginx`

## kill

- **Purpose:** Terminate process

- **Example:** `kill -9 1234`

## ip

- **Purpose:** Network interfaces & routes

- **Example:** `ip a`

## ping

- **Purpose:** Check connectivity

- **Example:** `ping -c 4 example.com`

## traceroute

- **Purpose:** Trace packet path

- **Example:** `traceroute example.com`

## dig

- **Purpose:** DNS lookup

- **Example:** `dig +short example.com`

## curl

- **Purpose:** HTTP requests & transfers

- **Example:** `curl -I https://example.com`

## wget

- **Purpose:** Download files

- **Example:** `wget https://example.com/file.tar.gz`

## scp

- **Purpose:** Secure copy over SSH

- **Example:** `scp file user@host:/path/`

## ssh

- **Purpose:** Secure shell login

- **Example:** `ssh user@server`

## tar

- **Purpose:** Archive/compress files

- **Example:** `tar -czf backup.tar.gz /var/www`

## zip

- **Purpose:** Zip archive utility

- **Example:** `zip -r site.zip site/`

## chmod

- **Purpose:** Change permissions

- **Example:** `chmod +x deploy.sh`

## chown

- **Purpose:** Change ownership

- **Example:** `chown user:group file`

## sudo

- **Purpose:** Run command as root

- **Example:** `sudo systemctl restart nginx`

## systemctl

- **Purpose:** Manage systemd services

- **Example:** `systemctl status docker`

## journalctl

- **Purpose:** Query systemd logs

- **Example:** `journalctl -u nginx`

## docker

- **Purpose:** Container management

- **Example:** `docker ps`
