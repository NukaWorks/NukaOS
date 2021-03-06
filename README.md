<h1 align="center">PowerOS - The Main repository</h1>

## Overview

### What is PowerOS ?

**PowerOS** is a fully free & opensource UNIX like operating system which target power & performance, a fully featured graphical user interface **(Workspace)** using the **NukaUI** design system.

### Idea & Concepts

The main objectif targeted is build a **fast and powerful** operating system, with the power of a **UNIX** system and a powerful & unique desktop environement.  
The whole **NukaWorks** ecosystem is build from scratch & we reuse forked projects.
like the Shell, CoreSystem and apps, and CoreBSD is re-imagined for a fully responsive & seamless usability.
We using the modern [**Rust**](https://www.rust-lang.org/) programing language, because it's a fully featured, fast and updated programing language.

### About this repository

This repo contains the default config for build a clean source-tree.
It's also contains stuff likes the PowerOS logo on the [**Icons**](https://github.com/NukaWorks/PowerOS/tree/master/Icons/) folder.  
It's also contains others things like documentation, scripts and screenshots.

<hr />

## Let's start

### Before you start

ℹ️  **PowerOS** is licensed under the [**GNU General Public License v3.0**](https://github.com/NukaWorks/PowerOS/blob/master/LICENSE).

### Contributing

***PlaceHolder***

## Cloning the source-tree

⚠️  Make sure if [**git**](https://git-scm.com/) and the **repo** tool (see below), is properly installed on your host system.

### Manage the project with repo
#### What is "repo" ?

*❝**repo** - The Multiple Git Repository Tool❞* - The repo tool is very useful for manage big project like Android ([***Android***](https://www.android.com/) uses the **repo** tool.) so that why PowerOS uses the **repo** tool.

The **repo** tool will read a file called ``default.xml``, the manifest. Finally repo will clone needed dependencies (specified in the manifest) on the project root directory.

ℹ️  **repo** can also update all projects one-time by typing the ``repo update`` command.


#### Installing the "repo" tool

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

### Sync the source-tree

Once the **git** and the **repo** setup, you can now clone the source-tree with it.  
Please move into a clean directory, you can make a `~/Projects/` Directory if you want.

⚠️  **Check if your host system have 20gb of free, if not, the operation can fails.**

#### Clone & Sync PowerOS

```sh
# Paste-it on your terminal and press enter.
repo init -u https://github.com/NukaWorks/PowerOS.git -b master
repo sync
```

#### Update the source-tree

**PowerOS** evolve with the time, so you need to keep the source-tree fully updated with the **repo** tool by using a few commands.

```sh
# Paste-it on your terminal and press enter.
repo update
```

## Building PowerOS

***PlaceHolder***

