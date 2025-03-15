# vmware

yay vmware-workstation
yay linux-headers

reboot

sudo systemctl enable vmware-networks.service;
sudo systemctl start vmware-networks.service;
sudo systemctl status vmware-networks.service;

sudo systemctl enable vmware-usbarbitrator.service;
sudo systemctl start vmware-usbarbitrator.service;
sudo systemctl status vmware-usbarbitrator.service;
