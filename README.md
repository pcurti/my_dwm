# my_dwm
needs picom
need fonts-hack-ttf

my .xinitrc:

~~~
~/.fehbg &
picom --experimental-backends -b &
dwmstatus 2>&1 >/dev/null &
exec dwm
~~~

my .fehbg:

~~~
#!/bin/sh
feh --no-fehbg --bg-fill '$HOME/bg.png'
~~~
