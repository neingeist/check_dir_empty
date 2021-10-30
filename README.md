# check_dir_empty
nagios plugin: check that the directories given are empty

## Example
~~~
$ ./check_dir_empty --no-count-empty /var/mail
OK: All given directories are empty
~~~

## Usage
~~~
% ./check_dir_empty -h
usage: check_dir_empty [-h] [--no-count-empty] dir [dir ...]

Check that the directories given are empty

positional arguments:
 dir               directory to be checked

optional arguments:
 -h, --help        show this help message and exit
 --no-count-empty  do not count empty files (useful to check /var/mail)
~~~
