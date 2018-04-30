# Cydia
A modified cydia

Adding custom links to the main interface


The background and the database have also changed


Add commodity link to custom price or introduce


Environmental requirements: CentOS Linux Nginx 1.12 MySQL 5.5 PHP-5.4 phpMyAdmin 4.4


I use these environments for testing. Perfect running is no problem. Other environments are self testing.


Install the method to upload to the root directory of the website, unzip, open your website and add /install into the installation program, enter the database address and account password according to the prompt, then set the name of the software source, the administrator account password, and automatically enter the background address, and the background address if the information is not completed and the information is completed. It's your domain name plus /admin


Modify the home page custom link in the root directory index.php file 298 lines to start modifying each modified address, you need to modify two locations, and there is one at the 757 line.

中文说明

改版的cydia


主界面增加自定义链接


后台和数据库也有所改动

后台增加商品链接自定义价钱或者介绍


环境要求:CentOS Linux  Nginx 1.12  MySQL 5.5  PHP-5.4 phpMyAdmin 4.4


我测试使用的是这些环境，完美运行没有问题，其他环境自行测试


安装方法:上传文件到网站的根目录,解压,打开你的网站后面加上/install进入安装程序,按照提示输入数据库地址和账号密码,然后设置软件源的名字,管理员账号密码，若信息没有填错设置完成信息后就自动进入后台管理地址了,后台地址是你的域名加/admin

修改主页自定义链接在根目录index.php文件298行开始修改每改一个地址需要修改两个位置还有一个在757行开始

