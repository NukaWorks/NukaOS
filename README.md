# NukaOS - The Main repository  

This repo contains the default config for build a clean source-tree.
It's contains also some stuff likes the NukaOS logo on **Icons/** folder.

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
repo init -u https://github.com/NukaWorks/NukaOS.git -b master
repo sync
```

