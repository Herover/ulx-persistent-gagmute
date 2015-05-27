# ulx-persistent-gagmute
Persistent gag&amp;mute commands for ulx

##Use

In chat: !tgag \<target\> [minutes]

Where minutes may be a number, a ulx timeString (1d = 1 day) or empty for permanent.

Same for tmute. Default access group is admins.

We use PData (a local sqlite database) but it should be simple to change this if needed.

##TODO:

* Add MySQL support/multiserver
* (perhaps) Add reasons
