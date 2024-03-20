Clickhouse role
=========

Роль для установки lighthouse.

Requirements
------------

- ansible==9.3.0
- ansible-base==2.10.8
- ansible-core==2.16.4

Variables
--------------

Все перезаписываемые переменные в defaults/main.yml
| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
|root_dir: | /data/www/ | Корневая директория для веб|

Example Playbook
----------------

Добавить в playbook:

    - hosts: servers
      roles:
         - { role: lighthouse-role }

License
-------

BSD

Author Information
------------------


