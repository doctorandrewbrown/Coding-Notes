- go to account in heroku dashboard scroll down to api key
- reveal key and copy
- open workspace for heroku connected repo
- in cmd line, 
```bash
$ heroku login -i
```
- at prompt, enter email and paste api
- when logged-in enter following (with app name) to get error log printed in terminal
```bash
$ heroku logs --tail --app community-appliances
```
