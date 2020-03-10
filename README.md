Flask RestPlus Patched
======================

Fork自[Jaza/flask-restplus-patched](https://github.com/Jaza/flask-restplus-patched)。
修改如下
1. 添加了一个DocumentSchema，对MongoDB的ORM MongoEngine的支持。原本就支持SQLAlchemy。
2. 添加了一个PostJSONParameters类，以处理接口json类型提交。

使用pip安装
`pip install git+https://github.com/simeon-xx/flask-restplus-patched.git`