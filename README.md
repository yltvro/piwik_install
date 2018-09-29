# piwik/Matomo 安装：<br>
## 系统环境RHEL7，PHP7，MySQL<br>
进入/var/www/html目录  <br>
$ git clone https://github.com/piwik/piwik.git<br>
$ cd piwik<br>
$ curl -sS https://getcomposer.org/installer | php<br>
$ cd /piwik <br>
$ php composer.phar install <br>
$ chown -R apache:apache /var/www/html/piwik <br>
在MySQL数据库中建立matomo库<br>
访问ip/piwik，按提示安装。
