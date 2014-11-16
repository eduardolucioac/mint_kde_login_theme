mint_kde_login_theme
=========

<img border="0" alt="GrooVim Doc" src="http://imageshack.com/a/img829/4064/meg6.png" height="15%" width="15%"/>GrooVim Doc

It's a MDM (HTML5) login theme made from "Razmo-MDM" theme. Here is a beautiful login theme made to replace the default Mint KDE, being better for "Plasma Desktop". We thank our friend "Razmo-MDM"!

Put the main folder into:

```
/usr/share/mdm/html-themes
```
Enjoy!

![alt tag](https://github.com/eduardolucioac/mint_kde_login_theme/blob/master/img/preview.jpg)

TIP!
-----

Your MDM KDE theme integration for Mint KDE would not be complete without the standard 
KDE cursor theme, because the Mint KDE uses the Ubuntu default. Below I show you how 
to fix it...

 * How to change MDM cursor theme on Linux Mint KDE (use KDE default):

After you install Linux Mint KDE which uses the MDM login screen by default, you may 
notice at the login screen the DMZ-White cursor theme is used. Here is how to make 
MDM use the Oxygen White cursor theme which is default in KDE. Since the GUI way 
is easier for, here is what I did the GUI way:

```
kdesu dolphin
```

Go to

```
/usr/share/icons/oxy-white/
```

Create a file named "cursor.theme"

Open it and put the following:

```
[Icon Theme]
Inherits=oxy-white
```

Go to

```
/etc/alternatives/
```

Find file/link

```
x-cursor-theme
```

Right click on it, edit the path in the link's Properties to point to your theme:

```
/usr/share/icons/oxy-white/cursor.theme
```

Save. Logout. Voila.
