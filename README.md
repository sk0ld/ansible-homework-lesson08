It's a very simple example of ansible usage without special tests.

Place dev and prod servers in /etc/ansible/hosts

[dev]
ip_or_hostname_dev

[prod]
ip_or_hostname_prod

To run playbook:

ansible-playbook dev-prod.yml