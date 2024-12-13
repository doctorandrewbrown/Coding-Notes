###  Cloning a github repo
- These steps apply to local work with VScode and Gitpod workspaces
- There is **no** need to create new empty directory to receive cloned repo
- The following cmd will create a new cloned directory containing all the files in the location you run it (e.g. home directory)
``` bash
$ git clone <github repo url>
```
- Type ```code .``` to open in vscode
- Once files are cloned you have a copy of the git repository already initialised (no need for ```git init``` ) run 
```bash
$ git remote -v 
```
- This will show the connected remote repo
``` bash
origin  https://github.com/doctorandrewbrown/original-repo.git (fetch)
origin  https://github.com/doctorandrewbrown/original-repo.git (push)
```
- If its your repo that's all you need to do
- If it's not your repo remove the original remote (named origin see above)
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
origin  https://github.com/doctorandrewbrown/new-remote.git (fetch)
origin  https://github.com/doctorandrewbrown/new-remote.git (push)
```
- Now, without making any commit locally (there are no changes yet) push files to new github repo 
```bash
$ git push -u origin main
```
- The repo will now be connected to github remote for push/pull. Check remote as before
```bash
$ git remote -v 
```
