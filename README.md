# BookManagement
Small Book Manager System write by php laravel 5
To use this, you need to do the following step

1. Install Xampp at https://www.apachefriends.org/.

2. After the Xampp's installation done, open Xampp control panel and start up Apache and MySQL.

3. Install Composer at https://getcomposer.org/

4. After the Composer's installation done, do the following step:
	- Open cmd.exe
	- Close all windows (include cmd.exe)
	- Open cmd.exe
	- Close cmd.exe and logout windows user, then login
	- Open cmd.exe
5. Copy BookManagement folder to ./xampp/htdocs/

6. Open file .env in BookManagement folder, change the DB_USERNAME and DB_PASSWORD if you are different

7. Open browser and enter http://localhost/phpmyadmin/ then create new database with name "bookmanagement"

8. Run Migration: go inside BookManagement folder, press Shift + Right click, choose "Open command window here" then enter "php artisan migrate" in the command window and press enter.

9. Run Seed database: continue at step 6, in command window, enter "php artisan db:seed" then press enter.

10. Finally, open browser and enter http://localhost/BookManagement/
