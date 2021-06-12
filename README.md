## ansible-gb
#### This is a project for practicing different practices using Ansible

### Roles used in this project
1. Creating user. Run create_user.yml
2. Creating empty file. Run touch_file.yml
3. Installation and configuration nginx with template file. Run install_nginx.yml
4. Creating directory and download file. Run download_file.yml
5. MySQL: setup, create user, create db, backup db. Run install_mysql.yml
6. Install Wordpress. Run install_wordpress.yml
6. Install PHP-FPM. Run install_fpm.yml

### Changes in the project
#### 12.06.2021
- Fix role install nginx. Add backups "www" and conf files nginx

- Added role for installation PHP-FPM (ver7.2)
if you can see the page at "http://your server IP/info.php" so it works!

#### 10.06.2021
- Added role for installation Wordpress (latest)
if you can see the page configuration at "http://your server IP" so it works!