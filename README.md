# How-to-Create-user-on-Alt-linux-and-add-him-to-sudoers

useradd -m net_admin

passwd net_admin

usermod -aG wheel net_admin

echo "net_admin ALL=(ALL:ALL) NOPASSWD:ALL" >> /etc/sudoers
