Chat System:

1. Software:
       Copy all files and folders from source code on your side (localhost)
2. Data base:
	You need to use Mysql
	a. DB Username: root
	b. DB Password: No password
	c. Make a DB name chat_db
	d. Run provided SQL in your phpMyAdmin
3. Run it on your localhost
4. You can login as: 
	‘user’ -> ‘password’, 
	‘moderator’ -> ‘password’ and 
	‘admin’ -> ‘password’ OR 
	register new user.


Note: if any of DB name, DB username, DB password or DB location is change you need to edit CMySQL.php file.

..\classes\CMySQL.php

        $this->sDbName = 'chat_db'; 	// 'YOUR_DB_NAME'
        $this->sDbUser = 'root';	// 'DB_USER_NAME'
        $this->sDbPass = '';		// 'DB_USER_PASS'

        $this->vLink = mysql_connect("localhost", $this->sDbUser, $this->sDbPass);	// 'DB_LOCATION'
