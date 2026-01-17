# update config.inc.php:
1. go to `/opt/www/roundcubemail/config/`
2. open `config.inc.php`
3. add line (if there isnt one): `$config['skin'] = 'merinos';`


# create links for plugins:
enter in comand line: 
`find /opt/www/roundcubemail/plugins -type d -name "elastic" -execdir ln -s elastic merinos \;`

# important info:

<small>This theme is based on Elastic roundcube theme whose author is Aleksander Machniak.</small>

For more info on how skins work go to: https://github.com/roundcube/roundcubemail/wiki/Skins
