# Setup k8s in any 3 node, single cluster setup

Should be working for DigitalOcean atleast. 
Please construct your own inventory file.

If you do not have Ansible experience, learn.
It's easy and handy, you can setup, k8s for example in no time. 

Just incase if you still wish to try it out, spin a Debian WSL image in Windows and install ansible-core by executing `apt update -y && apt upgrade -y && apt install -y ansible-core`.
Then, execute clone the repo and execute, `ansible-playbook -i <INVENTORY> install-k8s.yml`.

If you do not know how to build an inventory file, check out official guides for Ansible, or use and AI tools, they should help.

PS: Use dry-run command to check if the code will fail, then proceed with actual deployment. 
