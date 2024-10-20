# Linux终端常用命令

## 常见命令

mkdir 创建文件夹命令

cd 打开文件夹/查看文件夹内容(输入cd后双击tab)

## 终端挂起命令: screen命令(在运行长时间命令之前使用)

screen -S [name] 								创建终端

screen -ls											查看已存在的终端列表

screen -R [pid/name] 						进入终端/创建终端(R会检索同名, S不会)

screen -R(or S) [pid/name] -X quit 	清除中断命令(也可以在虚拟终端内输入exit)

screen -d [name]								转变终端状态(如终端在Attach状态下, 无法进入)