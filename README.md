# cmdOpenWithCurrentPath
Open cmd with current path under windows system by bat file. 

通过bat文件在windows系统下打开当前路径的cmd。

code/代码：
-
@echo off

cd /d %~dp0

start cmd

other methods/其他方法
-
Simply input cmd into file address bar.

直接在文件地址栏输入cmd就行了。
