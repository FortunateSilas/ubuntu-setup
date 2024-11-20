If you're using Linux Mint, start by closing the welcome page. We'll visit that later.

## Update the system

```sh
sudo apt update && sudo apt upgrade -y
```

## Supporting Libraries

```sh
sudo apt-get install -y software-properties-common python3-software-properties unzip tree libcurl4-gnutls-dev libexpat1-dev gettext libz-dev libssl-dev cmake gcc build-essential network-manager libnss3-tools jq xsel sed htop preload vlc
```

## Codecs (FIND A BETTER CODE)
```sh
sudo apt-get install codecs ffmpeg
```

## Firewall (Linux Mint)

`Profile` : Home
`Status` : On
`Incoming` : Deny
`Outgoing` : Allow

## Configure your favorite browser.
* Log in to the browser and enable sync
* Install Avira Password Manager
* Install Ghostly 
* Log in to github, store credentials to Avira

## Update & Clean Up
```sh
Sudo apt-get update && sudo apt-get upgrade
```

```sh
sudo apt-get autoremove
```

**Restart Your PC**