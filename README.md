# Dotfiles Setup for Ubuntu

This script installs the following components automatically:

- Docker
- Docker-Compose
- ZSH
- Oh-My-ZSH
- Powerlevel10k ZSH theme

## Setup Instructions

### Run from Cloud-Config
To run this script from "user-data" or "cloud-config" insert the following into the field:

```
#!/bin/bash

git clone https://github.com/mjtechguy/dotfiles-ubuntu-setup.git
cd dotfiles-ubuntu-setup
./setup.sh
```

Wait about 2 minutes for the setup to complete and login to the host.

### Run manually
Setup the server and login, then do the following.

- `git clone https://github.com/mjtechguy/dotfiles-ubuntu-setup.git`
- `cd dotfiles-ubuntu-setup`
- `./setup.sh`


