ABOUT
----------------------
Collabobase (Collaboration Base) is a simple web app that creates a collaboration environment
for an organization. Install it, create users, and they will be able to discuss and share files
between them, in addition to have a quick messagaing system.
Built on Codeigniter, NotORM, Twitter Bootstrap v3, and supports LTR and RTL.

REQUIREMENTS
----------------------
1. Apache v2.+, rewrite module is enabled.
2. MySQL
3. PHP 5.4+

INSTALL
----------------------
1. Copy the folder to a new apache folder.
2. Create a database in MySQL.
3. Import the schema.sql file into the database.
4. In app/config/database.php, update the host, username, password, and database name to which you have created.
5. You may need to change the .htaccess, the last line to add the correct URL just before index.php/$1
6. You need to issue the php composer install to install the requirements of the system. 

DB UPGRADING
----------------------
After checkout, upgrade the database by calling http://url_to_system/upgrade.

FIRST USE
----------------------
You can first login by the admin using the username: admin and password admin.
It is highly recommended to change them after the first installation.
From the admin menu, you can access the users section, where you can create new users and assign them roles.

WHAT IS INCLUDED
----------------------
This application uses CodeIgniter v2.1.4 (modified), NotORM (modified), Twitter Bootstrap v3 (modified), Arabic Twitter Bootstrap v3 (modified), Summernote WYSIWYG web editor, and Selectize bootstrap/jquery plugins.
