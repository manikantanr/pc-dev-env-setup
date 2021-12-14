#  Development Environment Setup

The scripts and commands I use to configure my fresh Linux and Windows development environments


# Windows 10/11

In Linux I use apt or yum to install almost all the required apps. In Windows, we can use  [Chocolatey](https://chocolatey.org) to do similar job.

But I want use latest windows tool, [WinGet](https://winget.run/).

## Installation of winget and winget pacakges

Visit https://winget.run/ and click on `Install winget` link on the navbar.

Once winget is installed use the following commands to install packages.


```bash
winget install -e --id VideoLAN.VLC
winget install -e --id SublimeHQ.SublimeText
winget install -e --id SublimeHQ.SublimeMerge
winget install -e --id JetBrains.IntelliJIDEA.Community
winget install -e --id JetBrains.PyCharm.Community
winget install -e --id Python.Python
winget install -e --id Google.Chrome
winget install -e --id KeePassXCTeam.KeePassXC
winget install -e --id Twilio.Authy



```
Sometimes, winget repository might have old version of software, then we can use of standard way of downloading and installing software using below links.

- https://www.nvidia.com/download/index.aspx?lang=en-us
- https://www.videolan.org/
- https://www.virtualbox.org/wiki/Downloads
- https://www.oracle.com/java/technologies/downloads/ or https://www.oracle.com/in/java/technologies/javase/jdk11-archive-downloads.html
- https://www.jetbrains.com/idea/download
- https://www.jetbrains.com/pycharm/download
- https://www.sublimetext.com/download
- https://www.sublimemerge.com/
- https://www.perforce.com/downloads/helix-visual-client-p4v
- https://code.visualstudio.com/download
- https://www.google.com/intl/en_in/chrome/
- https://www.7-zip.org/
- https://git-scm.com/downloads
- https://slack.com/intl/en-in/downloads/windows
- https://zoom.us/download
- https://keepassxc.org/download/#windows
- https://authy.com/download/
- 


# Linux

- https://authy.com/download/
```bash
sudo apt install ./google-chrome-stable_current_amd64.deb
sudo apt install vlc -y

wget https://get.docker.com/ -O docker_install.sh 
bash docker_install.sh
sudo usermod -aG docker $USER

sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose



```
