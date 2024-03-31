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

# composer

php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"

php -r "if (hash_file('sha384', 'composer-setup.php') === 'dac665fdc30fdd8ec78b38b9800061b4150413ff2e3b6f88543c636f7cd84f6db9189d43a81e5503cda447da73c7e5b6') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"

php -r "unlink('composer-setup.php');"

sudo mv composer.phar /usr/local/bin/composer

# nvm
curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash

nvm install --lts

sudo apt autoremove

# npm packages

curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash

nvm install --lts


## yarn & tldr
npm install --global yarn tldr
sudo mv composer.phar /usr/local/bin/composer
