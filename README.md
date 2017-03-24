# Shop

CREATE USER shop_dev IDENTIFIED BY '';
CREATE DATABASE shop_dev CHARACTER SET utf8 COLLATE utf8_general_ci;
GRANT ALL PRIVILEGES ON shop_dev.* TO 'shop_dev'@'%';
