#20251111
Install xampp 3.3.
PHP 8.2
Download https://getcomposer.org/Composer-Setup.exe install di komputer
Didalam xampp/htdocs/
xxxxx = bts, jaringan, sisdomain, blankspot
Gunakan command prompt
composer create-project --prefer-dist laravel/laravel xxxxx

buat databases untuk masing2 aplikasi yang dibangun
nama databases nya server_xxxxx
buat tabel: 
tab_admin
id int(11) auto increment Primary Key
nama varchar(50) Null
email varchar(50) Null 
no_hp varchar(30) Null 
aktivasi enum('1', '0') '0'
created_id int(11) Null
created_at datetime Null
updated_id int(11) Null
updated_at datetime Null
