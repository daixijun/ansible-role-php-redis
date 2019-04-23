Role Name
=========

[![Build Status](https://travis-ci.org/daixijun/ansible-role-php-redis.svg?branch=master)](https://travis-ci.org/daixijun/ansible-role-php-redis)

Ansible 安装php redis扩展

Requirements
------------

* RHEL/Centos 7
* Ansible 2.7 +

Role Variables
--------------

```yaml
php_redis_version: 4.3.0
php_redis_download_url: http://pecl.php.net/get/redis-{{ php_redis_version }}.tgz

```

Dependencies
------------

[daixijun.php](https://galaxy.ansible.com/daixijun/php)

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - role: daixijun.php
    - role: daixijun.php-redis
```

License
-------

BSD

Author Information
------------------

Xijun Dai <daixijun1990@gmail.com>
