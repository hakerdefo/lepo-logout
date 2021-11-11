# lepo-logout
**lepo-logout** is a lightweight, distribution agnostic utility for GNU/Linux systems that can,

- Lock screen<sup>[1](#footnote)</sup>
- Logout user
- Suspend system
- Reboot system
- Shutdown system

And **lepo-logout** doesn't require too many dependencies and resources to perform these tasks. **lepo-logout** doesn't even require ConsoleKit.


### Dependencies :
- YAD - YAD (Yet Another Display) is a program to display GTK+ dialogs. [YAD] is also known as Zenity on steroids. YAD is developed by Victor Ananjevsky. YAD is available in repositories of many current GNU/Linux distributions. If it is not available for installation via your distribution's package-manager you can download YAD from [SourceForge](https://sourceforge.net/projects/yad-dialog/) or [pkgs.org](http://pkgs.org/download/yad) or [UbuntuUpdates](http://www.ubuntuupdates.org/package_metas?exact_match=1&q=yad).


### Installation :
Installing **lepo-logout** on any GNU/Linux system is very easy. Just download [lepo-logout-master] zip file, extract its contents into a directory of your choice, open that directory in your favorite terminal emulator and run these two commands,
```sh
chmod 755 install-lepo-logout
```
```sh
sudo ./install-lepo-logout
```
Voila! **lepo-logout** is installed!


### Usage :
**lepo-logout** will be available under either **Preferences** or **System Tools** category of any Freedesktop standards compliant menu. You can easily launch **lepo-logout** by clicking on its menu entry. You can also run **lepo-logout** via your favorite terminal emulator by entering,
```sh
lepo-logout
```
You can also add **lepo-logout** to the panel for quick access. Please consult your panel's documentation on adding custom launchers. **lepo-logout**'s desktop file is located at **/usr/share/applications/lepo-logout.desktop**.


### Screenshot :
Here is a screenshot of **lepo-logout** just in case you were interested!

![alt text](http://i.imgur.com/FC793anl.png "Click to view the original image")


### Removal :
Removing **lepo-logout** from your system is just as easy. Open your favorite terminal emulator and run,
```sh
sudo remove-lepo-logout
```
Kaboom! **lepo-logout** is removed!


### Support :

If you like **lepo-logout**, please consider supporting it, even the smallest contribution goes a long way. It is quick & easy via PayPal, Buy Me a Coffee or Liberapay:  

[![Support via PayPal](https://cdn.jsdelivr.net/gh/twolfson/paypal-github-button@1.0.0/dist/button.svg)](https://paypal.me/hakerdefo)  
[!["Buy Me A Coffee"](https://user-images.githubusercontent.com/1376749/120938564-50c59780-c6e1-11eb-814f-22a0399623c5.png)](https://www.buymeacoffee.com/hakerdefo)  
[![Support via Liberapay](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/hakerdefo/donate)  


### Credits :
- Crystal Clear, GNOME, Human & Tango icon sets for the icons.
- Lennart Poettering for systemd & the name. lepo in the **lepo-logout** is a portmanteau of Lennart and Poettering.


### License :
This work (<span property="dct:title">lepo-logout</span>, by [<span property="dct:title">hakerdefo</span>](https://github.com/hakerdefo/lepo-logout)), identified by [<span property="dct:title">hakerdefo</span>](https://hakerdefo.blogspot.com), is released under [University of Illinois Open Source License](http://otm.illinois.edu/disclose-protect/illinois-open-source-license "University of Illinois/NCSA Open Source License").


#
<a name="footnote">1</a>. _Any one of the following will be required for the **Lock Screen** function,_

- _xtrlock_
- _i3lock_
- _slock_
- _light-locker_
- _xscreensaver_
- _gnome-screensaver_
- _dm-tool_

_If none of the above is installed, the **Lock Screen** button won't be visible in **lepo-logout**._

[YAD]:https://sourceforge.net/projects/yad-dialog/
[lepo-logout-master]:https://github.com/hakerdefo/lepo-logout/archive/master.zip
