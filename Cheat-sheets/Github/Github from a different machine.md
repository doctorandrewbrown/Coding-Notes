* First configure git for username and email as used for original github account
```shell
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```

* Clone a github repo into a new local providing PAT
```shell
$ git clone https://github.com/USERNAME/REPO.git
Username: YOUR_USERNAME
Password: YOUR_PERSONAL_ACCESS_TOKEN
```
* The PAT is stored locally in a file on original machine. If you can't find the original you can't recover it. But I think you can go into your github account and generate a new PAT and use that.