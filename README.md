# ubuntu-vm-boilerplate

A simple bash script to handle boilerplate configurations for cloned Ubuntu VMs (Machine ID, SSH server keys, Hostname)

Updated to reset the console font to make working on the Proxmox console on a laptop screen a little less painful, and to update the netplan configuration that anchors itself to an IP address.

## Usage

```sh
sudo bash -c "bash <(wget -qO- https://raw.githubusercontent.com/jenemoore/ubuntu-vm-boilerplate/master/run.sh)"
```
