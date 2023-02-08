# ssh_github
SSH wrapper to interact with github using SSH keys.

## Install
1. Copy .ssh into your user directory.
2. Add your SSH keys from github.
3. Make sure your .ssh folder has 700 permissions
4. Make sure your id_ed25519 ssh key has 600 permissions (both public and private)
5. Make sure the ssh_github script has 700 permissions

## Usage
1. Point programs to use ~/.ssh/ssh_github as their SSH path (i.e. setting the GIT_SSH environment variable).
2. The ssh_github script will add the SSH keys to every SSH call automatically, SSH can be used as normal.
