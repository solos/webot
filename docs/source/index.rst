.. webot documentation master file, created by
   sphinx-quickstart on Sun Apr 14 12:03:00 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

webot 文档
=================================

安装部署
-----------

webot依赖bottle和lxml，可以用pip安装


- 下载源码

    - git clone `git@github.com:solos/webot.git`

    - cd webot/webot

    - 修改config.py （TOKEN等参数）

    - mkdir ./log

- 安装bottle lxml

    - pip install bottle
    - lxml依赖lxbxml2和libxslt, debian/ubuntu: apt-get install libxml2 libxml2-dev libxslt1-dev

- 编译安装uwsgi和nginx

    
Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

