Java-飞飞
==========
飞飞(Fly for Fun)Java服务端.

贡献
=============
我们喜爱一起贡献的人,只需要提交合并请求,我们就会检查它.
在这个项目里请尽量使用Eclipse IDE环境.


许可信息
===================
    Copyright (C) 2014 Jon Huang <project54_jon@live.com>

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Affero General Public License as
    published by the Free Software Foundation, either version 3 of the
    License, or (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU Affero General Public License for more details.

    You should have received a copy of the GNU Affero General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

项目信息
===================

Java-飞飞是一个长期项目，目的是做出一个多平台程序(客户端和服务端)
可以适应任何环境，强调在Windows和Unix平台的可移植性.
我们现在的主要目标是开发一个稳定的可扩展的框架，类似于飞飞C++端.
然而我们主要的区别在于我们使用的库支持垮平台、多数据库支持.
主要是Java-飞飞，我们将使用MySQL为后台数据库，但是我们不会限制
用户选择用户使用其他数据库接口的权利(MariaDB，SQLite，等).


运行环境要求
====================

Java-飞飞需要兼容Java SE 7 的JVM环境.
下载地址: http://java.sun.com/javase/downloads/index.jsp

你还需要添加一些用到的库文件:

* [Apache MINA 2.0.7](http://mina.apache.org/downloads-mina.html)
* [MySQL Connector/J](http://dev.mysql.com/downloads/connector/j/)
* [Apache DBCP 2.0.1](http://commons.apache.org/proper/commons-dbcp/download_dbcp.cgi)
* [Apache Pool 2.2](http://commons.apache.org/proper/commons-pool/download_pool.cgi)
* [Apache DBUtils 1.6](http://commons.apache.org/proper/commons-dbutils/download_dbutils.cgi)
* [Apache Logging 1.2](http://commons.apache.org/proper/commons-logging/download_logging.cgi)
* [Apache Lang 3.3.2](http://commons.apache.org/proper/commons-lang/download_lang.cgi)
* [Joda-Time 2.4](https://github.com/JodaOrg/joda-time/releases)
* [slf4j 1.7.7](http://www.slf4j.org/download.html)

将来会使用的库文件:

* [JacORB 1.5](http://www.jacorb.org/download.html)
* [Google Guava 17.0](https://code.google.com/p/guava-libraries/downloads/list)
* [Apache Daemon 1.0.15](http://commons.apache.org/proper/commons-daemon/download_daemon.cgi)

最后你还必须有飞飞的数据文件.

Java-飞飞的后台数据库需要使用JDBC来访问,其他数据库没有测试.
我们推荐: [MySQL](http://dev.mysql.com).

注:我们没有包括库的许可证,但我们可以通过链接方便地下载库文件.