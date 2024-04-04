# php

#### Add php to the apt repository

```
sudo add-apt-repository ppa:ondrej/php
```

## Update & Upgrade the system

```
sudo apt update && sudo apt upgrade
```

#### Install php and essential extensions

sudo apt-get install php php-curl php-mbstring php-mcrypt php-xml php-zip php-mysqli php-bcmath php-posix

sudo apt update

# Installing Composer

# Get composer-setup.php
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"

# Verify the installer file
php -r "if (hash_file('sha384', 'composer-setup.php') === 'dac665fdc30fdd8ec78b38b9800061b4150413ff2e3b6f88543c636f7cd84f6db9189d43a81e5503cda447da73c7e5b6') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"

# Unlink the installer file
php -r "unlink('composer-setup.php');"

# Move composer to your bin folder
sudo mv composer.phar /usr/local/bin/composer

# nvm

# run the installer
curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash

# Install Node Version Manager
nvm install --lts

# clean up
sudo apt autoremove

# npm packages

## install yarn and tldryarn & tldr
npm install --global yarn tldr
