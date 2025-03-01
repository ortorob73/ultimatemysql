# ultimatemysql
MySQL database access wrapper compatible with PHP 8

Based on the excellent work of Jeff Williams
https://www.phpclasses.org/package/3698-PHP-MySQL-database-access-wrapper.html

### Why this repository
Despite it is being used by fortune 500 companies [[source](https://www.phpclasses.org/discuss/package/3698/thread/72/)], the script isn't update since 16/08/2013 (almost 10 years!), so i thinked to create this repository with the aim of making it compatible with PHP 8, and being able to use it for another 10 years (i hope!).

## How it work
It's a very simple database access wrapper, well documented and safe against SQL injection hacks!

You can start with only 3 lines!

```php
<?php
include("mysql.class.php");
$db = new MySQL(true, "testdb", "localhost", "root", "password");
$res = $db->QueryArray("SELECT * FROM Test");
?>
```

Check the "examples" directory to learn how it works, or read the [help.html](/help.html) file (a very good documentation)


## Contributions
Feel free to contribute to this project adding more feature or fixing issues, but before submitting a pull request, make sure your code passes all unit tests (refer to the [/tests/coverage.md](/tests/coverage.md) document)


## Support this / me
If you liked this work, and you haven't wasted hours of work with this repository, you can think about supporting me with Ko-fi

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/P5P5FY846)
