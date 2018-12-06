# ansible-provision-kali
Used to configure a base Kali machine to my specifications

This playbook does the following:
- Attempt to update the system completely
- Install Docker
- Install various packages
- Install SpaceVim (https://github.com/SpaceVim/SpaceVim)
- Install Z shell (https://github.com/robbyrussell/oh-my-zsh)
- Install my dotfiles and their associated dependencies (https://github.com/l50/dotfiles)

To pick and choose between any of these, simply comment out lines you're not interested in having in site.yml

# TODO:
- Add logs for ansible runs and logrotate
- Add Chrome
- Add SecLists
