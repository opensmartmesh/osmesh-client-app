# OpenSmartMesh Dashboard - osmesh-dashboard

Hybrid responsive client ionic application for the OpenSmartMesh Personal Dashboard


## How to use the app from this repository

 1. Clone this repository
 2. cd osmesh-dashboard/ ; npm install
 3. ionic serve

## Dependencies

### NodeJS

http://nodejs.org/
It provides you with the npm command, the NodeJS Packages Manager. It is needed
for the future installations.

#### Rpi3 - Raspbian

Note that for Raspbian, you need to manually install the latest ARM version as the default version in Raspbian tree is 0.10.x (quite old).

```
wget http://node-arm.herokuapp.com/node_latest_armhf.deb
sudo dpkg -i node_latest_armhf.deb
```

#### Rpi3 - Gentoo

```
echo "net-libs/nodejs" >> /etc/portage/packages.keywords
emerge -av nodejs
```

To be executed as root or sudoer:
 - On the first line you authorize the installation of the lastest unstable version of nodejs.
 - On the second line, you install nodejs and its dependecies.

### Ionic

http://ionicframework.com/

For all distribution, everytime you use -g then you need to be root or sudoer 

```
sudo npm install -g cordova ionic
```
