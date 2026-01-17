# update config.inc.php
1. go to `/opt/www/roundcubemail/config/`
2. open `config.inc.php`
3. add line (if there isnt one): `$config['skin'] = 'merinos';`


# create links for plugins
enter in comand line: `find /opt/www/roundcubemail/plugins -type d -name "elastic" -execdir ln -s elastic merinos \;`