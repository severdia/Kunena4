
## FORKED FROM KUNENA 4

Kunena 4 has a few bugs and a security issue that have been fixed in this Kunena 4.0.13 version.


## ABOUT

*Kunena* is a native Joomla forum and communications component written in PHP. *Kunena* enables forums, bulletin board, support forums, discussions and comments for a Joomla base website.


## REQUIREMENTS

*Kunena* 4.0 requires

    Joomla! 3.4: version 3.4.1 or greater (>= 3.4.3 recommended)
    PHP: version 5.3.1 or greater (>= 5.4.31 recommended) PHP7 Not Supported until Kunena 5.0!
    MySQL: version 5.1 or greater (>= 5.5 recommended)

Our installer will check for minimal version requirements and will abort the install if they are no met.

In addition we recommend the following PHP settings:

    max_execution_time     >= 30
    memory_limit           >= 32M  (>= 64M recommended) - depends on other Joomla extensions used
    safe_mode               = off
    upload_max_filesize    >= 3M
    GD, DOM, JSON support installed and OpenSSL only to embedded tweets

*Kunena* requires the following Joomla settings:

    * Mootools 1.4+ compatible template (Blue Eagle Template)
    * Bootstrap 2 compatible template (Crypsis Template)
    * Upgraded to latest versions all extensions that claim to integrate with Kunena
    * No plugins or modules that were developed for previous versions of Kunena or Fireboard


## INSTALLATION

*Kunena* is installed via the Joomla component/extension installer. 

The Joomla installers allows you to directly install *Kunena* via package URL or from a local download of yours.

As long as the minimum requirements are met, the Kunena install should take only a few moments. We have spent a great amount of time to automate the entire installation process.

Upgrades are performed just like new installs. There is no need to uninstall Kunena to perform an upgrade. We STRONGLY recommend that you perform a backup before and new software install or upgrade. The upgrade procedure is identical to a new install and is performed via the Joomla extension installer. *Kunena* will detect all prior version of Kunena and will perform the necessary upgrade tasks fully automatic.


## LICENSE

[GNU General Public License v3 or later](http://www.gnu.org/copyleft/gpl.html)
