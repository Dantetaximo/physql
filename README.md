# physql
Physical backups of all the PostgreSQL databases. Allows you to easily and quickly return to a snapshot of the database.
## Normal use
- Create a copy of PostgreSQL databases
```bash
./physql snapshot [dirname]
```
- Make changes in database
- Back to a snapshot file (restore all databases)
```bash
./physql restore [dirname]
```
## Requirements
- Edit variables in the script for your PostgreSQL version and directories
```bash
ver=9.6
data_dir="/var/lib/postgresql/"$ver
bin_dir="/usr/lib/postgresql/"$ver
```
- Notify (if you want desktop messages)
```bash
sudo apt install notify-osd
```
