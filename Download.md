===== Linux =====

It's always good to use prepared packages for your distribution. Search in distribution's repositories or in our [sourceforge download area](http://sourceforge.net/project/showfiles.php?group_id=16636).


  * **Suse/openSUSE**
    * [TOra repository](http://download.yarpen.cz/) - packages for openSUSE (11.x and later) and SLE too. All RPMs are built against Oracle 11.2 client. Packages contain tora (with Oracle support) and tora-no-oracle (MySQL and PostgreSQL) - all is available in the menu) (thanks to: [Packman](http://packman.links2linux.org/) )
  * **Gentoo** - TOra is in the main portage tree: //dev-db/tora//
  * **Mandriva**, **Fedora**, **RHEL**, **Mageia** - packages available at [sourceforge](https://sourceforge.net/projects/tora/files/tora/). Warning: packages can contain various dependencies.
  * **Debian** - only amd64 package for now at sourceforge.
  * **Ubuntu** - there is a package in //universe// repository but there are no additional info id it's available with Oracle support.

You can always build your own TOra from source code. See [[Development]] section for howto

===== MS Windows =====

There are Windows (64bit) binaries available in our [sourceforge download area](http://sourceforge.net/project/showfiles.php?group_id=16636).
  - .msi package - contains TOra installer. msi package supports both per-machine, and per-user(non-admin) installation
  - .zip package - contains TOra without installation program. Just "unpack and run".

**Important!** Because of legal reasons TOra comes without Oracle client drivers. If you need to access Oracle - you must install Oracle client (for example [oracle instant client](http://www.oracle.com/technology/software/tech/oci/instantclient/index.html) ).

===== Mac OS X =====

  - Mac standalone binaries are available (since version 2.1.1) in the [sourceforge download area](http://sourceforge.net/project/showfiles.php?group_id=16636) as DMG files - Mac's standard installation packages.
  - TOra is also available in [Macports](http://www.macports.org).

Visit [[MacOSX|Mac dedicated page]] for more.

===== Other operating systems =====

TOra can be compiled on every system where is Qt5 and Oracle client available. Probably. Let us know your experiences with it, please.

===== Documentation =====

You can download TOra documentation (the same one as presented in TOra's help) in [one pdf file](http://sourceforge.net/projects/tora/files/tora/tora_documentation.pdf/download).

Be sure and view the wiki at http://torasql.com