Support UTF-8 filename in Windows (Lua5.1 backport)
======

This lua library is for windows (mingw) only . It's similar to [lfs](https://keplerproject.github.io/luafilesystem) but support utf-8 filename. This fork is intended for a backport from [Cloudwu's Lua 5.3 based version](https://github.com/cloudwu/luawinfile) to the 5.1 that [Mudlet](https://github.com/Mudlet/Mudlet) uses.

**THIS PROJECT IS A WORK IN PROGRESS - IT IS NOT YET FUNCTIONAL IN Lua 5.1**

* lfs.dir ==> winfile.dir
* lfs.currentdir ==> winfile.currentdir
* lfs.chdir ==> winfile.chdir
* lfs.touch ==> winfile.touch
* lfs.mkdir ==> winfile.mkdir
* lfs.rmdir ==> winfile.rmdir
* lfs.attributes ==> winfile.attributes
* os.remove ==> winfile.remove
* os.rename ==> winfile.rename
* os.execute ==> winfile.execute
* os.getenv ==> winfile.getenv
* loadfile ==> winfile.loadfile
* dofile ==> winfile.dofile
* io.open ==> winfile.open
* io.popen ==> winfile.popen
* winfile.shortname : Get the shorname of the path.
* winfile.personaldir : Get My Document dir.
