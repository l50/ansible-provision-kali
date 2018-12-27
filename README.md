# ansible-provision-kali
[![License](http://img.shields.io/:license-mit-blue.svg)](https://github.com/l50/ansible-provision-kali/blob/master/LICENSE)

Used to configure a base Kali machine to my specifications

This playbook does the following:
- Attempt to update the system completely
- Install Docker
- Install Chrome
- Install various packages (complete list is in group_vars/all)
- Install SpaceVim (https://github.com/SpaceVim/SpaceVim)
- Install specified vim plugins
- Install Z shell (https://github.com/robbyrussell/oh-my-zsh)
- Install my dotfiles and their associated dependencies (https://github.com/l50/dotfiles)
- Install and configure logrotate for ansible logs
- Create cronjobs to automatically update my dotfile configuration and run ansible
- Add the SecLists repo
- Install X2Go Server

To pick and choose between any of these, simply comment out lines you're not interested in having in site.yml
