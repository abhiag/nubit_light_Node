# nubit_light_Node

**1️⃣Upgrade Ubuntu Packages & Create Screen for Nubit**

sudo apt-get update
sudo apt install git
sudo apt install nano
sudo apt install screen 
screen -S nubitga

**2️⃣Main one click Node install Command**

curl -sL1 https://nubit.sh | bash

🔸CTRL + A + D (this command is used to switch the running matrix Screen)
🔸Use this command to backup your Seeds: cat $HOME/nubit-node/mnemonic.txt
🔸to comeback on running node screen: screen -r nubitga

**to restart the node**
1️⃣Press Ctrl+C to stope the Node
2️⃣Then Put Curl Command: curl -sL1 https://nubit.sh | bash


