# jackr-linux-apps
[![Release Drafter](https://github.com/jackrschumacher/jackr-linux-apps/actions/workflows/release-drafter.yml/badge.svg)](https://github.com/jackrschumacher/jackr-linux-apps/actions/workflows/release-drafter.yml)

## Get list of installed appes via dkpg
* Make sure you are in the git repo
```
dpkg --get-selections > installedsoftware.log
```
## Install software on another system
* Make sure you are in the git repo
```
dpkg --set-selections > installedsoftware.log
dselect
apt-get dselect-upgrade
```

### Other info
* More info here: https://www.cyberciti.biz/tips/linux-get-list-installed-software-reinstallation-restore.html
