# Kali Build
This is a simple ansible playbook that I use to rebuild my Kali linux VMs periodically. Remembering all the configuration changes I have made over time is a pain, and this simplifies it. Currently it performs the following tasks:

- Clone my dotfiles
- Copy my tmux configuration to ~/.tmux.conf
- Configure git user.name and user.email
- 

# Running the Playbook
```
sudo apt install ansible
sudo whoami
ansible-playbook main.yml
```
sudo whoami is not required if you have enabled sudo to run without a password. 


