
### Connect remote repo to existing local
* First make and initialize local repo with ```git init```
* In github. create a repo to connect to
* In local terminal connect to remote
  ```bash
  $ git remote add origin https://github.com/doctorandrewbrown<remote_repo_name>
  $ git branch -M main
  $ git push -u origin main
  ```
* Check remote is connected with
  ```bash
  $ git remote -v
  ```
  giving confirmation of connection
  ```bash
  origin  https://github.com/doctorandrewbrown/<remote_repo_name> (fetch)
  origin  https://github.com/doctorandrewbrown/<remote_repo_name> (push)
  ```
* It is also possible to do this by creating a remote repo first.
