# bazaar-init

### Run this on each node to enable SSH

    su - root
    apt install git
    git clone https://github.com/benvneal88/bazaar-init.git

    cd bazaar-init
    chmod +x node_init.sh
    ./node_init.sh



Test ssh is enabled:
    ssh -i '/Users/ben/.ssh/bazaar_root_key' -o StrictHostKeychecking=no root@192.168.0.101