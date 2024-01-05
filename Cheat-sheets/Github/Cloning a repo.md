###  Cloning a github repo
-  In vscode or terminal create new empty directory to receive cloned repo
- cd into directory and 
``` bash
$ git clone <github repo url>
```
- Once files are cloned in terminal you have a copy of the git repository (no need for ```git init``` ) run 
```bash
$ git remote -v 
```
- This will show that the local clone is still set to push/pull from original remote repo eg.
``` bash
origin  https://github.com/doctorandrewbrown/original-repo.git (fetch)
origin  https://github.com/doctorandrewbrown/original-repo.git (push)
```
- Remove the original remote (named origin see above)
``` bash
$ git remote remove origin
```
- Check for remotes again as above and there will be no output to terminal
- In github create new empty repo to act as new remote and copy url from dashboard
- In vscode terminal set new remote eg.
``` bash
git remote add origin https://github.com/doctorandrewbrown/new-remote.git
```
- Check again with ```git remote -v``` to see new remote called origin connected 
```bash
origin  https://github.com/doctorandrewbrown/original-repo.git (fetch)
origin  https://github.com/doctorandrewbrown/original-repo.git (push)
```
- Now, without making any commit locally (there are no changes yet) push files to new github repo 
```bash
$ git push -u origin main
```
- The repo will now be connected to github remote for push/pull