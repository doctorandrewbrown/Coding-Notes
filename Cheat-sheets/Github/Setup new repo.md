# Git Notes

### Connect remote repo to existing local
* First initialize local repo with ```git init```
* Create a repo to connect to in github
* In local terminal connect with eg.
  ```bash
  $ git remote add origin https://github.com/doctorandrewbrown<remote_repo_name>
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
