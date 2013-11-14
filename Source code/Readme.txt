..\classes\CMySQL.php

        $this->sDbName = 'chat_db'; 	// 'YOUR_DB_NAME'
        $this->sDbUser = 'root';	// 'DB_USER_NAME'
        $this->sDbPass = '';		// 'DB_USER_PASS'

        $this->vLink = mysql_connect("localhost", $this->sDbUser, $this->sDbPass);	// 'DB_LOCATION'


