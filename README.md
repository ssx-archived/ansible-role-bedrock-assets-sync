ansible-role-bedrock-assets-sync
================================

To Use;

# ansible-playbook uploads.yml -i hosts/staging --extra-vars="site=example.com mode=pull"

or

# ansible-playbook uploads.yml -i hosts/staging --extra-vars="site=example.com mode=push"

Requirements/Dependancies
-------------------------

Bedrock Wordpress.

Role Variables
--------------

	remote_user: "{{ web_user }}"
	project: "{{ wordpress_sites[site] }}"
	project_root: "{{ www_root }}/{{ site }}"


License
-------

MIT

Author Information
------------------

Taken from this gist: https://gist.github.com/davenaylor/b41398a7f468837b10fc