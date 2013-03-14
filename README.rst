gmstatus
========

WEB

  http://jluedke.com/gmstatus

ABOUT

  gmstatus is a top like interface for a gearman cluster

  gmstatus is a console-based (non-gui) tool for monitoring a cluster
  of gearman servers via the status command. It should run on most
  platforms where python (gevent and curses) are installed

  On startup it will check for a configuration file with the format

  server=<gearmanN>
  server=<gearmanN>
  ..
  worker=<worker_name_regex>
  worker=<worker_name_regex>
  ...

  it will look for configuration files in
  .gmstatus 
  ~/.gmstatus 
  /etc/gmstatus

  Default server is 'localhost' and default worker pattern is '.*'

INSTALLATION

    python setup.py install

DOCUMENTATION

  gmstatus --help

AUTHOR

  James M. Luedke <contact@jluedke.com>

COPYRIGHT

  gmstatus is licensed under the GNU General Public License version
  2. For the full license information, please visit

  http://www.gnu.org/copyleft/gpl.html

NOTE
  IN DEVELOPMENT
