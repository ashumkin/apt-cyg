#  apt-cyg

## Description

Install tool for cygwin similar to debian apt-get

## Requirements

* wget
* bzip2
* tar
* (g)awk

## Commands

Command | Description
--------|-------------
install <package names> | install packages
localinstall <package names> | install packages from tars
remove <package names> | remove packages
outdated | list outdated packages
update | update setup.ini
upgrade | upgrade outdated packages
show | show installed packages
find <patterns> | find packages matching patterns
describe <patterns> | describe packages matching patterns
packageof <commands or files> | locate parent packages

## Options

Option | Description
--------|-------------
--prefix, -p <prefix> | prefix to install packages to (for debug purposes; must be set first)
--mirror, -m <url> | set mirror
--cache, -c <dir> | set cache
--fetch | fetch files only (not install)
--file, -f <file> | read package names from file
--force, -F | force install (for "install" only)
--noupdate, -u | don't update setup.ini from mirror
--help | show this help
--version | show version info

## License and Author

* Copyright:: 2005-9, Stephen Jungels
* Copyright:: 2013, Alexey Shumkin

Licensed under the GPL Version 1.0

    https://www.gnu.org/licenses/old-licenses/gpl-1.0
