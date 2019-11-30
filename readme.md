## About Laravel
Laravel 5.8 simple task scheduler:

See documentation on this link for scheduling options:
https://laravel.com/docs/5.8/scheduling#schedule-frequency-options

At last, add a single entry to your server’s crontab file:

* * * * * php /path/to/artisan schedule:run 1>> /dev/null 2>&1

OR

* * * * * cd /path-to-your-project && php artisan schedule:run >> /dev/null 2>&1

