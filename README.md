## Commands GitHub

```git init```

Initialize your Git repo.

```git status```

Check the status of your repo.

```git add```

add some change to the RAM so you can commit it later.

```git commit -m "message"```

Do a commit to master with your changes.

```git config```

Check the configurations of your git locally.

```git config  -list```

list of the changes.

```git config --global user.name "easieber"```

Change your configuration. In this case we are changing `user.name`.

```git show file.txt```

Show the history of a file.

```git add . ```

Add all changes 

```git diff```

See the changes in the terminal

```git diff "commit code" "commit code 2" ```

Comparing commits, if you want to see only one, then use only one commit code

``` git reset "commit code" --hard / --soft ```

Go back to a older version by forcing or normal

```git log --stat```

See the changes made in all files. In case the the changes are to long use arrows to go up and down and use `q` to go out of this.

```git checkout "commit code" "file.txt"```

See first version of the porject. using the code of the commit.

```git rm```

remove files without removing its history

``` git rm --cached```

Remove files in staging and will remove it from the next commit, but it will still be in the hard drive.

``` git rm --force```

Remove everything, but rememeber that git save everything.

``` git reset --soft```

We delete all the history and register in Git, but we will save the changes that we have in staging.

```git reset --hard```

You will delete EVERYTHING. Todo Todito.

``` git reset HEAD```

with this we take out files from the staging area so they will not be commited.

```git push```

Push your change to the server

<Foto>

```git fetch```

Bring the repository to the local repository

```git merge```

Merge de repository in the server to the local directory

<Foto>

``` git pull```

Bring everything form the server to the local directory and repository

<Foto> 