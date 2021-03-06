Suru Icon Theme
================

Suru is a FreeDesktop icon theme whose design is based upon and around the original Suru icon guidelines for Ubuntu mobile applications.

Many of the original Ubuntu generic app icons and Unity8 symbolic icons have been repurposed for desktop use, however the icon set has extensive additions such as icons for folders, devices, file types, application categories, and other system toolbar and status icons.

## Notes

 - This set is designed for desktop environment coverage only, pull requests or issues regarding branded icons or theming third-party applications (for example, Firefox) will be rejected.
 - Any issues or pull requests regarding icons specifically for desktop environments, such as MATE, XFCE, etc., will be attended to as they come.
 - A theme that includes icons for third-party apps and branded icons is under development but is separate from this set.
 - This icon set inherits icons from Humanity icon theme (if installed) to fill in the gaps

## Copying or Reusing

This project is licenced under the terms of the [GNU General Public License, version 3](https://www.gnu.org/licenses/gpl-3.0.txt), so you are free to copy and reuse accordingly.

## Installing & Using

**Please note: this icon theme is in development, as such there are plenty of icons that are "missing" or incomplete**

There are no official packages or releases (yet) but you can install this theme from source with the provided [Makefile](/Makefile) and a few commands.

From the root directory of this repository running `make install` will install Suru to your home folder. After which you should be able to pick Suru as your icon theme or set it with:

    gsettings set org.gnome.desktop.interface icon-theme Suru

You can install Suru system-wide with `sudo make install-root` but you needn't do that if you're the only user.

### Removing Suru

To remove Suru, simply run: `make uninstall` or, depending on whether or not you installed it with superuser priveleges: `sudo make uninstall-root` 

## Support

The development of Suru is, in part, supported by [Patreon](http://patreon.com/snwh/), your patronage is much appreciated. &#x1F60A;

