# nginx-le-deploy
debian 10 nginx with lets encrypt ansible playbook

ansible-playbook -u root -i d10n.inventory deb10_nginx-le.yml

after running the playbook, point DNS, then:

certbot --nginx

follow the interactive certbot prompt, then test/tune from there
