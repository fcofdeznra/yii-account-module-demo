yii-account-module-demo
=======================

Demo of account module for Yii framework

Installation
------------

* Unpack account module demo under your web server directory.

* [Download account module](https://github.com/fcofdeznra/yii-account-module) and unpack it under modules directory.

* Execute account/data/schema.mysql.sql script in your database.

* Configure database connection:

```
[php]
'db'=>array(
	'connectionString' => 'mysql:host=localhost;dbname=account-module',
	'username' => 'account-module',
	'password' => 'account-module',
),
```

