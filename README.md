# Ubuntu laptop-setup

```
sudo apt-get install -y git python-pip
sudo pip install ansible
git clone https://github.com/hcvst/laptop-setup.git
cd laptop-setup
ansible-playbook -K -i "localhost," -c local setup.yml
```
