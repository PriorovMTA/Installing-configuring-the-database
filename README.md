# Installing-configuring-the-database


# Установка базы данных:
# dev - имя пользователя, priorov_password - пароль
1. sudo apt update 
2. sudo apt install phpmyadmin php-mbstring php-zip php-gd php-json php-curl
3. sudo apt install phpmyadmin
4. sudo phpenmod mbstring
5. sudo apt-get install mysql-server
6. sudo mysql
7. CREATE USER 'dev'@'localhost' IDENTIFIED WITH caching_sha2_password BY 'priorov_password';
8. GRANT ALL PRIVILEGES ON *.* TO 'dev'@'localhost' WITH GRANT OPTION;


# libmysqlclient20 в Ubuntu 20
# Фикс летающего текста в консоли

1. sudo apt update
2. sudo apt-get install libmysqlclient-dev
3. sudo apt install libmysqlclient21


# Пропись прав ядру, если нужно.
chmod u+x mta-server64

# Установка "tmux"
sudo apt install tmux
