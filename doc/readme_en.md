# EasyBackup Web Manger


EasyBackup Web Manger is a Java Web Manager based on the  [EasyBackup framework Engine](https://github.com/ushelp/EasyBackup "移步 EasyBackup"), you can complete the backup configuration, start and stop control.

To use, please learning  [EasyBackup](https://github.com/ushelp/EasyBackup "Goto EasyBackup")。


## Use

1. Make backup-web.war deployed to a Web container (Tomcat, Jetty ...)

2. Visit http://127.0.0.1:8888/easybackup-web/

## Features

### Dashboard
Start, stop, monitor backup service running.

![EasyBackup web manager](images/dashboard.png)

### Configuration list
Backup configuration list of services; view, edit, delete, enable, disable service items. 

![EasyBackup web manager](images/configurations_zh_CN.png)

### New Backup Service Configuration
Add a new backup service configuration.

![EasyBackup web manager](images/new_zh_CN.png)

### The global default configuration
The default global configuration backup service configuration.

![EasyBackup web manager](images/global_zh_CN.png)

### Help
Configuration examples.

![EasyBackup web manager](images/help_zh_CN.png)


## Project configuration information

### EasyBackup profiles
**Reminder**: If necessary, please note the following core backup configuration files to prevent accidental deletion operation and maintenance of the backup configuration you create.

- Backup core profile `/easybackup.properties` 
- Send e-mail template directory `/template/`

### EasyBackup Web I18N profiles

- I18N configuration `/WEB-INF/classes/easybackup_lang_country.properties`










## End

[The official home page](http://www.easyproject.cn/easybackup/en/index.jsp 'The official home page')

[Comments](http://www.easyproject.cn/easybackup/en/index.jsp#donation 'Comments')

If you have more comments, suggestions or ideas, please contact me.

Email：<inthinkcolor@gmail.com>

[http://www.easyproject.cn](http://www.easyproject.cn "EasyProject Home")



We believe that the contribution of each bit by bit, will be driven to produce more and better free and open source products a big step.

**Thank you donation to support the server running and encourage more community members.**

[![PayPal](http://www.easyproject.cn/images/paypaldonation5.jpg)](https://www.paypal.me/easyproject/10 "Make payments with PayPal - it's fast, free and secure!")

