# d-composer
_PHP Composer Docker image_

It allows you to run PHP Composer command without install it just by running **d-compose** command. Example:
```bash
d-compose install
```
If you need to run it as _root_ you can add ```--root``` option after **d-compose**.


## What you need?
You need Docker for running this script. Instructions how to install it you can find here - [Docker intsallation](https://docs.docker.com/install/linux/docker-ce/ubuntu/#install-docker-ce-1).

## Install
You need just to download the script and make it executable.
```bash
sudo wget https://raw.githubusercontent.com/micobg/d-composer/master/d-composer -qO /usr/local/bin/d-composer
sudo chmod +x /usr/local/bin/d-composer
d-composer --version
```
Thats all!
