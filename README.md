# ZECmate APT repository

Use the following to set it up. 
```
echo 'deb https://zecmate.github.io/aptrepo/ all main' | sudo tee --append /etc/apt/sources.list.d/zecmate.list
gpg --keyserver keyserver.ubuntu.com --recv 4B69CA27A986265D
gpg --export 4B69CA27A986265D | sudo apt-key add -

sudo apt-get update
sudo apt-get install zecmate # Installs ZECmate Swing Wallet, Zcash is needed to be installed, check: https://z.cash/download.html
```

## Available Packages
```
## AMD64
zecmate
        Depends: default-jdk, zcash
```
