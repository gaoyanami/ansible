# Role
## 1 Create Role
    ansible-galaxy mininet

## 2 Install ShadowSocks Server

    ansible-playbook -i inventory/hosts shadowsocks.yml  -e ansible_ssh_port=27216 -k -u root
