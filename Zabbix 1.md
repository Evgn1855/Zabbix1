### **Задание 1.** Установите Zabbix Server с веб\-интерфейсом. 

|  sudo apt install postgresql wget [https://repo.zabbix.com/zabbix/6.0/debian/pool/main/z/zabbix-release/zabbix-release\_latest\_6.0+debian13\_all.deb](https://repo.zabbix.com/zabbix/6.0/debian/pool/main/z/zabbix-release/zabbix-release_latest_6.0+debian13_all.deb)  sudo dpkg \-i zabbix-release\_latest\_6.0+debian13\_all.deb sudo apt install zabbix-server-pgsql zabbix-frontend-php php8.4-pgsql zabbix-apache-conf zabbix-sql-scripts nano \-y sudo \-u postgres createuser \--pwprompt zabbix sudo \-u postgres createdb \-O zabbix zabbix sudo systemctl start zabbix-server.service sudo systemctl enable zabbix-server.service zcat /usr/share/zabbix-sql-scripts/postgresql/server.sql.gz | sudo \-u zabbix psql zabbix sudo find / \-name zabbix\_server.conf sudo apt install zabbix-agent |
| :---- |

![ссылка](images/image1.png)
![ссылка](images/image2.png)

### **Задание 2\.** Установите Zabbix Agent на два хоста

### 

![ссылка](images/image3.png)
![ссылка](images/image4.png)
![ссылка](images/image5.png)
![ссылка](images/image6.png)

### **Задание 3\.** Установите Zabbix Agent на Windows (компьютер) и подключите его к серверу Zabbix. 

![ссылка](images/image7.png)
![ссылка](images/image8.png)
![ссылка](images/image9.png)
![ссылка](images/image10.png)
![ссылка](images/image11.png)


![ссылка](images/zabbix.jpg)
