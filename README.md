# How to upgrade python2.7.5 to python 2.7.13

1. Install python2-pip package

    yum -y install epel-release

    yum -y install python2-pip

    OR

    yum -y install http://dl.fedoraproject.org/pub/epel/7/x86_64/p/python2-pip-8.1.2-5.el7.noarch.rpm

2. Upgrade pip package

    pip install -U pip

3. Upgrade python to 2.7.13

    yum -y upgrade python-2.7.13-1.el7.centos.x86_64.rpm python-libs-2.7.13-1.el7.centos.x86_64.rpm

