# System Rental Camera with CodeIgniter 3.19
<p align="center"><a href="https://codeigniter.com/" target="_blank"><img src="https://cdn.worldvectorlogo.com/logos/codeigniter.svg" width="400"></a></p>

## How to Setup a CodeIgniter Project you cloned from Github.com

Requirement:
```markdown
PHP 7.4+
XAMPP
```

1. Clone GitHub repo for this project locally
```markdown

git clone git@github.com:risdatamamal/rental-camera.git rental-camera

```

2. After Clone Github repo, cd into your project. And then Install Composer Dependencies and NPM Dependencies
```markdown
composer install

composer update
```

3. Connect to MySQL in application/config/database.php
```markdown
$db['default'] = array(
	'dsn'	=> '',
	'hostname' => 'localhost',
	'username' => 'root',
	'password' => '',
	'database' => 'rental',
	'dbdriver' => 'mysqli',
	'dbprefix' => '',
	'pconnect' => FALSE,
	'db_debug' => (ENVIRONMENT !== 'production'),
	'cache_on' => FALSE,
	'cachedir' => '',
	'char_set' => 'utf8',
	'dbcollat' => 'utf8_general_ci',
	'swap_pre' => '',
	'encrypt' => FALSE,
	'compress' => FALSE,
	'stricton' => FALSE,
	'failover' => array(),
	'save_queries' => TRUE
);
```

4. Migrate the database
```markdown

php index.php migrate

```
