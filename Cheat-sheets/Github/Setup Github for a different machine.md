* First, on new machine, make a new directory locally to clone into. Don not initialize as a repo as we will be cloning an existing repo from github.
* Open cmd line for directory in vscode etc. and configure git for username and email as used for original github account. You can get username and email using ```git config --list``` on original machine.
```
```shell
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```

* Clone a github repo into the new local directory (without ```git init```)
```providing PAT
```shell
$ git clone https://github.com/USERNAME/REPO.git
Username: YOUR_USERNAME
Password: YOUR_PERSONAL_ACCESS_TOKEN
```
* The PAT is stored locally in a file on original machine so email to self. If you can't find the original you can't recover it. But I think you can go into your github account on original machine and generate a new PAT and use that. 
* It should now be possible to push/pull to github and machine will be authenticated.