# setup-kube-cluster

How to setup:
1. Make sure you have installed Ansible on your laptop
2. clone the repo
   git clone https://github.com/TaufanWisnu/setup-kube-cluster.git ~/setup-kube-cluster
3. edit host file then change control-plane IP and worker
   cd ~/setup-kube-cluster/
   nano hosts
4. Run the following script to start the installation
   ansible-playbook -i hosts ~/setup-kube-cluster/setup-kube-cluster.yaml
     
   
