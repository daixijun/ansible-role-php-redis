# daixijun.php-redis

[![Build Status](https://github.com/daixijun/ansible-role-php-redis/workflows/build/badge.svg)](https://github.com/daixijun/ansible-role-php-redis/actions)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-daixijun.php-redis-660198.svg?style=flat)](https://galaxy.ansible.com/daixijun/php-redis/)
[![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/daixijun/ansible-role-php-redis?sort=semver)](https://github.com/daixijun/ansible-role-php-redis/tags)

Ansible 安装php redis扩展

## 环境要求

* RHEL/Centos 7+
* Ansible 2.7 +

## 变量

```yaml
php_redis_version: 4.3.0
php_redis_download_url: http://pecl.php.net/get/redis-{{ php_redis_version }}.tgz
```

## 依赖

[daixijun.php](https://github.com/daixijun/ansible-role-php)

## 示例

```yaml
- hosts: servers
  roles:
    - role: daixijun.php
    - role: daixijun.php-redis
```

## License

BSD

## 维护者

* Xijun Dai <daixijun1990@gmail.com>
