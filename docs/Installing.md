Civetweb Install Guide
====

This guide covers the distributions for CivetWeb.  The latest source code is available at https://github.com/sunsetbrew/civetweb.

Windows
---

This pre-built version comes pre-built wit LUA support.  There is no SSL support included due to licensing restrictions; however, users can build Civetwab SSL themselves.
 
1. Install the [Visual C++ Redistributable for Visual Studio 2012](http://www.microsoft.com/en-us/download/details.aspx?id=30679)
2. Download latest *civetweb64_setup.msi* (64 bit) or *civetweb32_setup.msi* (32 bit) from [SourceForge](https://sourceforge.net/projects/civetweb/files/)
3. Run the installation program.
4. Civetweb will be in the programs menu.
5. When started, Civetweb puts itself into the tray.

OS X
---

This pre-built version comes with LUA, IPV6 and SSL support.

1. Download the latest *Civetweb.dmg* from [SourceForge](https://sourceforge.net/projects/civetweb/files/)
2. Click on the it and look for the attachment in the finder.
4. Drag Civetweb to the Applications folder.
5. When started, Civetweb puts itself into top menu.

Linux
---

1. Download the latest *civetweb.tar.gz* from [SourceForge](https://sourceforge.net/projects/civetweb/files/)
2. Open archive and change to the new directory.
3. make help
4. make
5. make install
6. Run the program ```/usr/local/bin/civetweb```, it will use the configuration file */usr/local/etc/civetweb.conf*.