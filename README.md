### Description

These are a set of roles baked into a playbook to provision a vagrant machine with all the tools required to start developing python projects.

I started with:

1. A common app to install:
	* PostgreSQL
	* Redis
	* Nginx
	* Build-essential
2. Virtualenv & Virtualenvwrapper for Python 2.7
3. an example django role which:
	* Creates a virtualenv with specified project name
	* Installs my project's requirements (project_dir/requirements.txt)

