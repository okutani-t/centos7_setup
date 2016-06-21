# CentOS7 SETUP

Setup CentOS7 environment for Vagrant. Installs nginx, PostgreSQL, redis, MongoDB, PHP, Ruby on Rails, Node.js, Golang. See site.yml for more details.

Please install if you have not yet vagrant-vbguest

```
$ vagrant plugin install vagrant-vbguest
```

Get centos7_setup proj.

```
$ git clone --recursive https://github.com/okutani-t/centos7_setup.git
```

Remove # in site.yml

```
- # connection: local
+ connection: local
```

Rewrite group_vars/all.yml yourself...

Run.

```
$ cd centos7_setup
$ vagrant up
```

author: okutani
