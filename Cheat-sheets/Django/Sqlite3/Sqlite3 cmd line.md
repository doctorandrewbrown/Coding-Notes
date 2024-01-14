- In gitpod workspace you have to re-install sqlite each time you start the work 
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
- alternative way to get to sqlite3 in Django 
```bash
$ python3 manage.py dbshell
sqlite> SELECT * FROM ....
```