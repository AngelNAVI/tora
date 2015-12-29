===== Linux =====

It's always good to use prepared packages for your distribution. Search in distribution's repositories or in our [[http://sourceforge.net/project/showfiles.php?group_id=16636|sourceforge download area]].


  * **Suse/openSUSE**
    * [[http://download.yarpen.cz/|TOra repository]] - packages for openSUSE (11.x and later) and SLE too. All RPMs are built against Oracle 11.2 client. Packages contain tora (with Oracle support) and tora-no-oracle (MySQL and PostgreSQL) - all is available in the menu) (thanks to: [[http://packman.links2linux.org/|Packman]])
  * **Gentoo** - TOra is in the main portage tree: //dev-db/tora//
  * **Mandriva**, **Fedora**, **RHEL**, **Mageia** - packages available at [[https://sourceforge.net/projects/tora/files/tora/|sourceforge]]. Warning: packages can contain various dependencies.
  * **Debian** - only amd64 package for now at sourceforge.
  * **Ubuntu** - there is a package in //universe// repository but there are no additional info id it's available with Oracle support.

You can always build your own TOra from source code. See [[Development]] section for howto

===== MS Windows =====

There are Windows (32bit) binaries available in our [[http://sourceforge.net/project/showfiles.php?group_id=16636|sourceforge download area]].
  - Setup package - contains TOra installer.
  - Zip package - contains TOra without installation program. Just "unpack and run".

**Important!** Because of legal reasons TOra comes with a stub //oci.dll// file which makes it possible to use TOra with non Oracle databases even when Oracle client is not installed. If you need to access Oracle - you must install Oracle client (for example [[http://www.oracle.com/technology/software/tech/oci/instantclient/index.html|oracle instant client]]) and delete stub //oci.dll// from TOra installation folder.

===== Mac OS X =====

  - Mac standalone binaries are available (since version 2.1.1) in the [[http://sourceforge.net/project/showfiles.php?group_id=16636|sourceforge download area]] as DMG files - Mac's standard installation packages.
  - TOra is also available in [[http://www.macports.org|Macports]].

Visit [[MacOSX|Mac dedicated page]] for more.

===== Other operating systems =====

TOra can be compiled on every system where is Qt4 and Oracle client available. Probably. Let us know your experiences with it, please.

===== Documentation =====

You can download TOra documentation (the same one as presented in TOra's help) in [[http://sourceforge.net/projects/tora/files/tora/tora_documentation.pdf/download|one pdf file]].

Be sure and view the wiki at http://torasql.com