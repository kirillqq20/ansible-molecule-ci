# ansible-molecule-ci
# install
sudo apt update
sudo apt install python3
sudo apt install python3-pip
sudo pip3 install molecule

pip install molecule[docker]

# init scenario in role
molecule init scenario

# 
molecule converage