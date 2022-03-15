# Install VM

# add user to sudoers group
gpasswd -a ${USER} sudo

apt-get update && apt-get upgrade

apt-get install vim
