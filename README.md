# centos7_setup

Setup CentOS7 environment for Vagrant. Installs nginx, PostgreSQL, redis, MongoDB, PHP, Ruby on Rails, Node.js, Golang. See site.yml for more details.

```
# Please install if you have not yet vagrant-vbguest
# $ vagrant plugin install vagrant-vbguest

# remove # in site.yml
# - # connection: local
# + connection: local

$ git clone --recursive https://github.com/okutani-t/centos7_setup.git
$ cd centos7_setup
$ vagrant up

```

author: okutani
