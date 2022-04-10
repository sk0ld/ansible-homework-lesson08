   
It's a very simple example of ansible usage without special tests.

Place dev and prod servers in /etc/ansible/hosts



[prod]

ip_or_hostname_prod



[dev]

ip_or_hostname_dev


To run playbook:

ansible-playbook dev-prod.yml

To check the result:

http://ip_or_hostname_prod:8080/hello-1.0
