# Raspberry Pime Capsule

An Ansible playbook for setting up a Raspberry Pi with an external drive as a Time Capsule

#### Dependencies
* paramiko
* ansible 2+
* Raspberry Pi with Raspbian Jessie

### Run This Command
```
ANSIBLE_HOST_KEY_CHECKING=False ansible-playbook -vvvv -i "{{raspberry_pi_ip}}," playbook.yml
```

### Playbook Compiled From
* http://netatalk.sourceforge.net/wiki/index.php/Install_Netatalk_3.1.7_on_Debian_8_Jessie
* http://www.calebwoods.com/2015/04/06/diy-time-capsule-raspberry-pi/
