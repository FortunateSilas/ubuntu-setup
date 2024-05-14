# Install WordPress Cli

## Download the wp-cli.phar file
```
curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar
```

## Make the phar file executable
```
chmod +x wp-cli.phar
```

## Move the phar file to the local bin
```
sudo mv wp-cli.phar /usr/local/bin/wp
```

# Install Laravel Installer

```
composer global require "laravel/installer"
```