#一、demo
###  1.本项目主要发布和收集一些常用的exploit！ ---by backlion  联系QQ:601462930
###  2.我的博客：http://www.backlion.org
###  3.需要特别的说，我会在说明文档中注明使用说明！
-------------------------------------------------------------
#exploit常见问题说明：
1.weblogic.py为JAVA反序列号脚本：
使用命令为：python  weblogic.py  主机名或者IP地址   端口号


2.eYouMail.py为邮箱心脏流血验证脚本：
使用命令：python eYouMail.py  主机名  端口号


3.CVE2016-0728.C为linux提权exp,编译步骤：
如需要安装缺少的编译文件：yum install keyutils-libs-devel
编译命令：gcc cve2016-0728.c -o  cve2016-0728
使用方法：./cve2016-0728

4.killchian.py为kali2.0的集中控制管理接口：
使用方法：python killchina.py

5.CVE-2016-1879.py为freebsd系统的DOS攻击exp,用户如下：
在KALI下：python CVE-2016-1879.py  -m 目标MAC地址 -i 目标的IPV6地址  -I eth0(接口）

