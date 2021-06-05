# JosephWorks PPA
My Personal Package Archive

## Installation

```bash
sudo add-apt-repository "deb [arch=amd64] http://repo.josephworks.net:8081/repository/josephworks $(lsb_release -cs) main"
wget http://repo.josephworks.net:8081/repository/files/public.gpg.key && sudo apt-key add public.gpg.key && rm public.gpg.key
sudo apt update
```

## Softwares

* AdoptOpenJDK
* Atom
* Brackets
* Nvidia CUDA Repo
* Docker
* Dockstation
* Discord
* Dropbox
* GitKraken
* Google Chrome
* Google Earth Pro
* Google WebDesigner
* Hyper
* Jenkins
* Kitematic
* MDATP (Microsoft Defender Active Threat Protection)
* MegaCMD
* MegaSync
* Minecraft Launcher
* MultiMC
* MySQL Connector Java
* Nvidia TensorRT Repo
* Nvidia Machine Learning repo
* QEMU
* Teams
* Termius
* Tilix
* WebMin
* Zoom

Check http://repo.josephworks.net:8081/#browse/search/apt=repository_name%3Djosephworks for a full list of softwares.

> Note: Have one of these already installed? Apt will pull the latest file from Ubuntu Repo if it is outdated on my repo (and vice versa). This only applies to packages that are on other repos.

## Repo Stats

Targeted for Ubuntu Latest (not LTS)
Nexus 3 (latest version)

### Ubuntu Archive Mirror

The PPA Repository server also hosts a mirror of the Ubuntu Archive.

Check it out here: https://launchpad.net/ubuntu/+mirror/repo.josephworks.net-archive

## Add a Package

Want to see a package added to the repo? Just create an issue!
