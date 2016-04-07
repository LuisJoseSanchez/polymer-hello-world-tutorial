# Polymer Hello World tutorial

Table of contents
=================

  * [Polymer installation](#polymer-installation)
    * [Install NodeJS](#install-nodejs)
    * [Update `npm`](#update-npm)
    * [Install Bower](#install-bower)
    * [Create project folder](#create-project-folder)
    * [Create `bower.json` file](#create-bower.json-file)
    * [Install Polymer](#install-polymer)
  * [Install `paper-dialog`](#install-paper-dialog)
    
    
    Create `bower.json` file

## Polymer installation

This installation has been tested successfully in **Ubuntu 15.10**

### Install NodeJS

Add NodeJS to the repositories and install:

```console
curl -sL https://deb.nodesource.com/setup_5.x | sudo -E bash -
sudo apt-get install -y nodejs
```

Check the installation:

```console
node -v
```

### Update `npm`

```console
sudo npm install npm -g
```

Check the installation:

```console
npm -v
```

### Install Bower

```console
sudo npm install -g bower
```

Check the installation:

```console
bower -v
```

### Create project folder

```console
mkdir PolymerHello
cd PolymerHello
```

### Create `bower.json` file

```console
bower init
```

### Install Polymer

```console
bower install --save Polymer/polymer
```

## Install `paper-dialog`

```console
bower install --save PolymerElements/paper-dialog
```

