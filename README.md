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
