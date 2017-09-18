#!/bin/bash
sudo apt-get update
sudo apt-get install -y git
sudo git clone https://github.com/davidavaboomers/z.git
cd $HOME/z/
chmod +x install
./install

SCRIPT_PATH=$(realpath $0)
rm $SCRIPT_PATH 
