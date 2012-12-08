luci-app-aria2
==============

luci-app-aria2    Patch


Put this  patch file in   trunk/feeds/luci/luci/patches 

And Edit the file trunk/feeds/luci/luci/Makefile ,add the fllowing codes  


$(eval $(call application,aria2,LuCI Support for Aria2,\
  +PACKAGE_luci-app-aria2:aria2))

Then you will found  luci-app-aria2  in  make menuconfig -> Luci -> applitions