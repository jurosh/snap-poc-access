# snap-poc-access

Only POC for testing access for keybaor dlisten events and other areas from snaps.

## Build

```
sudo snap install lxd && sudo lxd init # if you don’t have LXD already
sudo usermod -a -G lxd $USER && newgrp lxd # if your user is not in the lxd group already
sudo snap install --classic snapcraft # if you don’t have snapcraft already

git clone https://github.com/jurosh/snap-poc-access
cd snap-poc-access
snapcraft cleanbuild --debug
```
