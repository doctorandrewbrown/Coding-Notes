- When in a Django project you can interact directly with the sqlite database to see what's going on
- In gitpod you have to re-install sqlite each time you start the workspace 
``` bash
 $ sudo apt update
```

- then 
``` bash
$ sudo apt install sqlite3
```
- For sqlite3 prompt to run SQL commands
``` bash
$ sqlite3
sqlite> SELECT * FROM ....
```
- alternative way to get to sqlite3 prompt in Django is to use 
```bash
$ python3 manage.py dbshell
sqlite> SELECT * FROM ....
```