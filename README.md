# mysql-php-apache-notes
Notes about installation of MySQL database PHP connection<br>
**Warning: mysqli::__construct(): (HY000/1044): Access denied for user**<br>
_FIX_ : tick _Check all_ of **Global Privileges**<br>

**Unpack the latest version of Moodle into the c:\xampp\htdocs folder.**

**Fix php_intl.dll extension in php.ini :**<br>
Add:<br> 
**extension= php_intl.dll**<br>
**intl.default_locale = en_utf8**<br>
**intl.error_level = E_WARNING**<br>

to **c:\xampp\php\php.ini**<br>
**restart XAMPP to update changes**
~~extension= php_sodium.dll~~ not working <br>
~~extension= sodium~~ not working <br>
