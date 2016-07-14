# Lingonberry Theme for Grav

![Lingonberry](assets/readme_1.png)

A clean and simple theme for bloggers, with responsive design and beautiful typography by [Anders Norén](http://www.andersnoren.se/teman/lingonberry-wordpress-theme/).

# Features

* Simple and Clean Layout
* Post Formats
* Blog Layout
* Beautiful Design
* Slideshows inside posts
* Featured Images
* Video posts support
* Supports YouTube
* Supports SoundCloud
* Supports Vimeo
* SimpleSearch support
* Recent posts
* Simple calendar
* JSComments plugin support
* Comments and Forms plugin support

# Installation

Installing the Lingonberry theme can be done in one of two ways. Our GPM (Grav Package Manager) installation method enables you to quickly and easily install the theme with a simple terminal command, while the manual method enables you to do so via a zip file.

The theme by itself is useful, but you may have an easier time getting up and running by installing a skeleton. The [Lingonberry Site Skeleton](https://github.com/getgrav/grav-skeleton-lingonberry-site) is a self-contained repository for a complete sites which includes: sample content, configuration, theme, and plugins.

## GPM Installation (Preferred)

The simplest way to install this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's Terminal (also called the command line).  From the root of your Grav install type:

    bin/gpm install lingonberry

This will install the Lingonberry theme into your `/user/themes` directory within Grav. Its files can be found under `/your/site/grav/user/themes/lingonberry`.

## Manual Installation

To install this theme, just download the zip version of this repository and unzip it under `/your/site/grav/user/themes`. Then, rename the folder to `lingonberry`. You can find these files either on [GitHub](https://github.com/getgrav/grav-theme-lingonberry) or via [GetGrav.org](http://getgrav.org/downloads/themes).

You should now have all the theme files under

    /your/site/grav/user/themes/lingonberry

>> NOTE: This theme is a modular component for Grav which requires the [Grav](http://github.com/getgrav/grav), [Error](https://github.com/getgrav/grav-plugin-error) and [Problems](https://github.com/getgrav/grav-plugin-problems) plugins.

# Updating

As development for the Lingonberry theme continues, new versions may become available that add additional features and functionality, improve compatibility with newer Grav releases, and generally provide a better user experience. Updating Lingonberry is easy, and can be done through Grav's GPM system, as well as manually.

## GPM Update (Preferred)

The simplest way to update this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm). You can do this with this by navigating to the root directory of your Grav install using your system's Terminal (also called command line) and typing the following:

    bin/gpm update lingonberry

This command will check your Grav install to see if your Lingonberry theme is due for an update. If a newer release is found, you will be asked whether or not you wish to update. To continue, type `y` and hit enter. The theme will automatically update and clear Grav's cache.

## Manual Update

Manually updating Lingonberry is pretty simple. Here is what you will need to do to get this done:

* Delete the `your/site/user/themes/lingonberry` directory.
* Download the new version of the Lingonberry theme from either [GitHub](https://github.com/getgrav/grav-theme-lingonberry) or [GetGrav.org](http://getgrav.org/downloads/themes).
* Unzip the zip file in `your/site/user/themes` and rename the resulting folder to `lingonberry`.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in terminal and typing `bin/grav clear-cache`.

> Note: Any changes you have made to any of the files listed under this directory will also be removed and replaced by the new set. Any files located elsewhere (for example a YAML settings file placed in `user/config/themes`) will remain intact.

# Setup

If you want to set Lingonberry as the default theme, you can do so by following these steps:

* Navigate to `/your/site/grav/user/config`.
* Open the **system.yaml** file.
* Change the `theme:` setting to `theme: lingonberry`.
* Save your changes.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in Terminal and typing `bin/grav clear-cache`.

Once this is done, you should be able to see the new theme on the frontend. Keep in mind any customizations made to the previous theme will not be reflected as all of the theme and templating information is now being pulled from the **lingonberry** folder.

# Available post types

There are several post formats available. You can set them by customizing **type** page header variable. For example
```
type: video
```
Available post types are: aside, audio, chat, gallery, image, link, quote, status, video. Each selections contains different icon and formatting.

# Slideshows

You can add slideshow to your posts by customizing slideshow page header variable. For example:

```
slideshow:
  - title: "Audio 1 M Compact Stereo"
    image: 1.jpg
  - title: "Vitsœ 606 Universal Shelving System"
    image: 2.jpg
  - title: "SK4 Music Center"
    image: 3.jpg
  - title: "Vitsœ 606 Universal Shelving System"
    image: 4.jpg
```

# Credits

* Font Awesome icons license : SIL Open Font License 1.1 http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL
* Fitvids.js license : WTFPL http://www.wtfpl.net/
* Flexslider 2 license : GPLv2 http://www.gnu.org/licenses/gpl-2.0.html
* Lato font license : SIL Open Font License, 1.1 http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL
* Raleway font license : SIL Open Font License, 1.1 http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL
* screenshot.png header image : Public Domain http://en.wikipedia.org/wiki/Public_domain (taken by the theme author)
* screenshot.png post image : CC0 Public Domain http://creativecommons.org/publicdomain/zero/1.0/
