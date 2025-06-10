Installing Dify on Windows Ubuntu subsystem.

1. Install Ansible
'
sudo apt update
sudo apt install ansible
'

2. Clone github repo https://github.com/jjankar/ai-agents-k8s.git

'
git clone https://github.com/jjankar/ai-agents-k8s.git
'

3. Get into folder wher Ansible playbooks are

'
cd ai-agents-k8s/dify
'

4. Run playbook
'
ansible-playbook -i inventory_local.ini install_dify_local.yml
'
5. Go to the page http://localhost
