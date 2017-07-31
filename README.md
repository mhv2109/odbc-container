# airflow-dags-container

Add UnixODBC to your [Ansible Container](https://github.com/ansible/ansible-container) project.

Additional ODBC packages can be installed by adding them to {{ odbc_packages }}.
Add ```odbc.ini``` and ```odbcinst.ini``` templates and update {{ ODBCINI }} and {{ ODBCINSTINI }} to their paths in your project.

```
# Set the working directory to your Ansible Container project root
$ cd myproject

# Install the service
$ ansible-container install ansible.odbc-container
```