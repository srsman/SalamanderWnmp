# SalamanderWnmp
WPF制作的wnmp环境
# UI界面

![SalamanderWnmp](https://cloud.githubusercontent.com/assets/16663435/19766037/36fbe8fa-9c7e-11e6-92b1-d4537ca1cc0c.jpg)

# 注意
php 版本为7.0.1 64位版本，需要MSVC14 (Visual C++ 2015)运行库支持，下载：https://download.microsoft.com/download/9/3/F/93FCF1E7-E6A4-478B-96E7-D4B285925B00/vc_redist.x64.exe



# 配置

集成包下有文件：配置.txt
## php
修改php.ini中的extension_dir配置，改为php目录下ext目录的绝对路径

## nginx

修改conf目录下nginx.conf中的localhost虚拟主机的root（网站根目录），改为某个目录（譬如D:/web_root）的绝对路径（使用/，使用\会出错）

## mysql

修改my.ini文件中base_dir和data_dir的配置，分别修改为mysql目录和mysql目录下的data目录的绝对路径




