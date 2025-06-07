# VICE GitHub Mirror
This is the official git mirror of the [VICE subversion repo](https://sourceforge.net/p/vice-emu/code/HEAD/tree/).

For news, documentation, developer information, [visit the VICE website](https://vice-emu.sourceforge.io/).

## Download VICE
* [Official Releases](https://vice-emu.sourceforge.io/#download)
* [Snapshot builds of the latest code](https://github.com/VICE-Team/svn-mirror/releases)

## exrom fork

changes to VICE GitHub Mirror:  
add support for git versioning (while keeping svn support):
gensvnversion.sh now determines git hash or the svn rev - whatever the workspace is versioned with.
If no version control is present, gensvnversion.sh generates empty revision string, so there is 
no need for the many USE_SVN_REVISION switches in source files any more.
Related patches
https://sourceforge.net/p/vice-emu/patches/381/
https://sourceforge.net/p/vice-emu/patches/385/
