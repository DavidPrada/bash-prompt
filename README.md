#Git bash-prompt
Git bash prompt with personal customizations

Forked from: https://github.com/magicmonty/bash-git-prompt

##Example
![alt tag](https://raw.github.com/DavidPrada/bash-prompt/master/bash-prompt.png)

##Features
- Terminal title displays username@hostname
- Time
- Red for root, green for normal users
- cd includes ls (only in interactive prompts)
- git information (only in git folders)
- Red ❌ if the last terminal command fails

##Installation
```
sudo mkdir /usr/local/scripts
sudo git clone https://github.com/DavidPrada/bash-prompt /usr/local/scripts/bash-prompt
echo -e "\nsource /usr/local/scripts/bash-prompt/gitprompt.sh\n" >> ~/.bashrc
echo -e "\nsource /usr/local/scripts/bash-prompt/gitprompt.sh\n" | sudo tee -a /root/.bashrc
```