# ansible-playbook -i inventory -e ansible_user=centos -e ansible_password=DevOps321 03-nginx.yaml
# ansible -i inventory mongodb --list-host
# ansible -i inventory mongodb -m ping -e ansible_user=centos -e ansible_password=DevOps321
# ansible -i inventory mongodb -m ping -u centos --ask-pass
# ansible -i inventory mongodb --become -e ansible_name=centos -e ansible_password=DevOps321 -m ansible.builtin.yum -a "name=nginx state=installed"
# ansible -i inventory mongodb -b -e ansible_name=centos -e ansible_password=DevOps321 -m ansible.builtin.service -a "name=nginx state=installed"
