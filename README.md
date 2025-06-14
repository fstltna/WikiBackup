# MediaWiki backup script (1.9.1)
Creates a backup of your MediaWiki installation and MySQL data

Official support sites: [Official Github Repo](https://github.com/fstltna/WikiBackup)

---

1. create a cron job like this:

        1 1 * * * /root/WikiBackup/wikibackup.pl

2. This will back up your MediaWiki installation at 1:01am each day, and keep the last 5 backups.

3. Edit the backup config:

 	Run a manual backup and it will ask you for the mysql config info. If you need to reconfigure it use the "prefs" command-line option

If you need more help visit https://wikihosting.gameplayer.club/
