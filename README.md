# ansible-provision-kali
Used to configure a base Kali machine to my specifications

This playbook does the following:
- Attempt to update the system completely
- Install Docker
- Install Chrome
- Install various packages (complete list is in group_vars/all)
- Install SpaceVim (https://github.com/SpaceVim/SpaceVim)
- Install Z shell (https://github.com/robbyrussell/oh-my-zsh)
- Install my dotfiles and their associated dependencies (https://github.com/l50/dotfiles)
- Install and configure logrotate for ansible logs
- Create cronjobs to automatically update my dotfile configuration and run ansible

To pick and choose between any of these, simply comment out lines you're not interested in having in site.yml

# TODO:
- Add SecLists
- Add x2go
- Add auto install curl command
