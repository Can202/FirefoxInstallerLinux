# FirefoxInstallerLinux
Firefox Installer to have automatic updates

# Instructions

## Option 1

1. Download the installer:
- [64-bits](https://github.com/Can202/FirefoxInstallerLinux/releases/download/v0.3/firefox_installer_64)
- [32-bits](https://github.com/Can202/FirefoxInstallerLinux/releases/download/v0.3/firefox_installer_32)

2. Make it executable

3. Run in terminal

## Option 2

1. run this in terminal as root (or with an admin user)

- 64-bits
~~~
sudo echo && cd /tmp/ && wget https://github.com/Can202/FirefoxInstallerLinux/releases/download/v0.3/firefox_installer_64 && chmod a+x firefox_installer_64 && ./firefox_installer_64 && rm firefox_installer_64
~~~
- 32-bits
~~~
sudo echo && cd /tmp/ && wget https://github.com/Can202/FirefoxInstallerLinux/releases/download/v0.3/firefox_installer_32 && chmod a+x firefox_installer_32 && ./firefox_installer_32 && rm firefox_installer_32
~~~

2. If the command failed, do this and try the first step again:

- 64-bits
~~~
sudo rm /tmp/firefox_installer_64
~~~
- 32-bits
~~~
sudo rm /tmp/firefox_installer_32
~~~

# Dependencies

- wget
- git
- tar
- lolcat (optional, but it's cool)

# Commands

- --help

see available commands

- --remove

remove firefox

- do [command]

send a firefox command

- do --help

see firefox commands
