# Structured documents

Kill port
>lsof -i:1337

JSdoc in atom shortcut
> Control-Shift-d or Control-Shift-j to add comment templates.


LOCAL ENVS
> process.env.DATABASE_URL = 'mysql://root:root@localhost:3306/archpim';
> process.env.REDIS_URL = 'redis://localhost:6379';

Edit host 
> cd /etc/hosts

Change site avialabe for apache
> sudo /etc/apache2/site-avilable/00 ...

Run added site
> sudo a2ensite

Rewrite apache conif
> sudo a2enmod rewrite


My sql wyrzucenie zmiennej globalnej
~~~
mysql -u root -p
~~~
~~~mysql
mysql> set global sql_mode='STRICT_TRANS_TABLES,NO_ZERO_IN_DATE,NO_ZERO_DATE,ERROR_FOR_DIVISION_BY_ZERO,NO_AUTO_CREATE_USER,NO_ENGINE_SUBSTITUTION';
mysql> set session sql_mode='STRICT_TRANS_TABLES,NO_ZERO_IN_DATE,NO_ZERO_DATE,ERROR_FOR_DIVISION_BY_ZERO,NO_AUTO_CREATE_USER,NO_ENGINE_SUBSTITUTION';
~~~~

Znalezienie promisa

~~~js
process.on('unhandledRejection', (reason, p) => {
	console.log('Unhandled Rejection at: Promise', p, 'reason:', reason);
	// application specific logging, throwing an error, or other logic here
});
~~~

