# KetchupOS

## Main repository
### Cloning the source-tree
#### Installing repo

```sh
mkdir -p ~/.bin
PATH="${HOME}/.bin:${PATH}"
curl https://storage.googleapis.com/git-repo-downloads/repo > ~/.bin/repo
chmod a+rx ~/.bin/repo
```
#### Sync the source-tree

```sh
repo init -u https://github.com/KetchupOS/KetchupOS-default.git -b master
repo sync
```