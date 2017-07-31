# airflow-dags-container

Add UnixODBC to your [Ansible Container](https://github.com/ansible/ansible-container) project.

Additional ODBC packages can be installed by adding them to {{ odbc_packages }}.

```
# Set the working directory to your Ansible Container project root
$ cd myproject

# Install the service
$ ansible-container install ansible.odbc-container
```