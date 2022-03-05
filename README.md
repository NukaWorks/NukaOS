<h1 align="center">NukaOS - The Main repository</h1>

## Overview

### What is nukaOS ?

**NukaOS** is a fully free & opensource UNIX like operating system which target power & performance, a fully featured graphical user interface **(Workspace)** using the **NukaUI** design system.

### About this repository

This repo contains the default config for build a clean source-tree.
It's also contains stuff likes the NukaOS logo on the [**Icons**](https://github.com/NukaWorks/NukaOS/tree/master/Icons/) folder.

<hr />

## Let's start

### Before you start

***PlaceHolder***

### Contributing

***PlaceHolder***

### Cloning the source-tree

⚠️  Make sure if [**git**](https://git-scm.com/) and the **repo** tool (see below), is properly installed on your host system.

#### The powerful repo tool
##### What is "repo" ?

*❝**repo** - The Multiple Git Repository Tool❞* - The repo tool is very useful for manage big project like Android (Android uses the **repo** tool.) so that why NukaOS uses the **repo** tool.

The **repo** tool will read a file called ``default.xml``, the manifest. Finally repo will clone needed dependencies (specified in the manifest) on the project root directory.

ℹ️  **repo** can also update all projects one-time by typing the ``repo update`` command.


##### Installing the "repo" tool

First of all, you need to open a terminal which using a bash prompt and copy-paste commands below on your terminal.

```sh
# Paste-it on your terminal and press enter.
mkdir -p ~/.bin
PATH="${HOME}/.bin:${PATH}"
curl https://storage.googleapis.com/git-repo-downloads/repo > ~/.bin/repo
chmod a+rx ~/.bin/repo
```

⚠️  If you close your terminal, you can't relaunch **repo** if you havn't do this :

-- Add it on your `~/.profile` or `~/.bashrc` **(shell config file)**

```sh
# Paste-it on your shell config file.
export PATH="${HOME}/.bin:${PATH}"
```

As you can see, while you relaunch a terminal, the **repo** tool is now available.

#### Sync the source-tree

Once the **git** and the **repo** setup, you can now clone the source-tree with it.  
Please move into a clean directory, you can make a `~/Projects/` Directory if you want.

⚠️  **Check if your host system have 20gb of free, if not, the operation can fails.**

##### Clone & Sync NukaOS

```sh
# Paste-it on your terminal and press enter.
repo init -u https://github.com/NukaWorks/NukaOS.git -b master
repo sync
```

#### Building NukaOS

***PlaceHolder***

