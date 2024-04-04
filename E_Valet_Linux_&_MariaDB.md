# Install Valet Linux & MariaDB

## Check to see if apache2 is still in the system

which apache2

sudo /etc/init.d/apache2 stop
sudo apt remove apache2

## Install Valet Linux via composer
```
composer global require cpriego/valet-linux
```

## Add composer packages to PATH
```
sed -i 's|:$PATH|:$HOME/.config/composer/vendor/bin:$PATH|g' ~/.zshrc
```

## Install valet
```
valet install
```

## Set the default domain
```
valet domain www
```

## Install MariaDB (MySQL)
```
sudo apt-get install mariadb-server
```

```
sudo mysql -uroot
```

```
use mysql;
```

```
SELECT User, Host FROM mysql.user;
```

```
mysql > DROP USER 'root'@'localhost';
```

```
CREATE USER 'root'@'localhost' IDENTIFIED BY '';
```

```
GRANT ALL PRIVILEGES ON *.* TO 'root'@'localhost' WITH GRANT OPTION;
```

```
FLUSH PRIVILEGES;
\q
```

```
mysql -uroot
```
# phpmyadmin
wget https://www.phpmyadmin.net/downloads/phpMyAdmin-latest-all-languages.zip