## About Laravel
Laravel 5.8 simple task scheduler:

At last, add a single entry to your server’s crontab file:

* * * * * php /path/to/artisan schedule:run 1>> /dev/null 2>&1

OR

* * * * * cd /path-to-your-project && php artisan schedule:run >> /dev/null 2>&1

