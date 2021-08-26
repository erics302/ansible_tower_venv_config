## Description

Add or modify virtual environments on ansible tower servers.

## Custom Variables

See [`playbook.yml`](playbook.yml).

Custom Variables listed below:

| Variable | Description |
| --- | --- |
| venv_list | List of virtual environment names |
| tower_venv_directory | This is the path on tower servers to create venv.  Tower uses the default location of /var/lib/awx/venv/ |


### Example requirements
```
ansible==2.9.6
Jinja2==2.11.2
psutil
```