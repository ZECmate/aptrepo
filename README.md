# TheTrunk APT repository

Use the following to set it up. 
```
echo 'deb https://thetrunk.github.io/releases/ all main' | sudo tee --append /etc/apt/sources.list.d/thetrunk.list
gpg --keyserver keyserver.ubuntu.com --recv 69FAF6DE41B8AC51
gpg --export 69FAF6DE41B8AC51| sudo apt-key add -

sudo apt-get update
sudo apt-get install zcashswingwallet # Installs Zcash Swing Wallet and Zcash binaries
```

## Available Packages
```
## AMD64
zcashswingwallet
        Depends: default-jdk
```