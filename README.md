# Pinpress Theme for Grav

![Pinpress](assets/readme_1.png)

PinPress is a creative Flat Blog/Magazine grav theme and it is the perfect choice for professionals who’s looking for a magazine theme or a personal, niche, corporate, and marketing blogs. PinPress grav theme is highly customizable so it can match your personal taste and be quickly converted into a multi-purpose theme as well. It's a port of PinPress blogger template by [Sora Templates](http://www.soratemplates.com/).

# Features

* Navigation menu included
* Clean Layout
* Blog Layout
* Minimalistic
* FeedBurner support
* Social Sharing
* Browser Compatibility
* Supports YouTube
* Supports SoundCloud
* Supports Vimeo
* SimpleSearch support
* Feeds
* RelatedPosts plugin support
* Archives plugin support
* JSComments plugin support
* Comments and Forms plugin support

# Installation

Installing the Pinpress theme can be done in one of two ways. Our GPM (Grav Package Manager) installation method enables you to quickly and easily install the theme with a simple terminal command, while the manual method enables you to do so via a zip file.

The theme by itself is useful, but you may have an easier time getting up and running by installing a skeleton. The [Pinpress Site Skeleton](https://github.com/getgrav/grav-skeleton-pinpress-blog) is a self-contained repository for a complete sites which includes: sample content, configuration, theme, and plugins.

## GPM Installation (Preferred)

The simplest way to install this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's Terminal (also called the command line).  From the root of your Grav install type:

    bin/gpm install pinpress

This will install the Pinpress theme into your `/user/themes` directory within Grav. Its files can be found under `/your/site/grav/user/themes/pinpress`.

## Manual Installation

To install this theme, just download the zip version of this repository and unzip it under `/your/site/grav/user/themes`. Then, rename the folder to `pinpress`. You can find these files either on [GitHub](https://github.com/getgrav/grav-theme-pinpress) or via [GetGrav.org](http://getgrav.org/downloads/themes).

You should now have all the theme files under

    /your/site/grav/user/themes/pinpress

>> NOTE: This theme is a modular component for Grav which requires the [Grav](http://github.com/getgrav/grav), [Error](https://github.com/getgrav/grav-theme-error) and [Problems](https://github.com/getgrav/grav-plugin-problems) plugins.

# Updating

As development for the Pinpress theme continues, new versions may become available that add additional features and functionality, improve compatibility with newer Grav releases, and generally provide a better user experience. Updating Pinpress is easy, and can be done through Grav's GPM system, as well as manually.

## GPM Update (Preferred)

The simplest way to update this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm). You can do this with this by navigating to the root directory of your Grav install using your system's Terminal (also called command line) and typing the following:

    bin/gpm update pinpress

This command will check your Grav install to see if your Pinpress theme is due for an update. If a newer release is found, you will be asked whether or not you wish to update. To continue, type `y` and hit enter. The theme will automatically update and clear Grav's cache.

## Manual Update

Manually updating Pinpress is pretty simple. Here is what you will need to do to get this done:

* Delete the `your/site/user/themes/pinpress` directory.
* Download the new version of the Pinpress theme from either [GitHub](https://github.com/getgrav/grav-theme-pinpress) or [GetGrav.org](http://getgrav.org/downloads/themes).
* Unzip the zip file in `your/site/user/themes` and rename the resulting folder to `pinpress`.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in terminal and typing `bin/grav clear-cache`.

> Note: Any changes you have made to any of the files listed under this directory will also be removed and replaced by the new set. Any files located elsewhere (for example a YAML settings file placed in `user/config/themes`) will remain intact.

# Setup

If you want to set Pinpress as the default theme, you can do so by following these steps:

* Navigate to `/your/site/grav/user/config`.
* Open the **system.yaml** file.
* Change the `theme:` setting to `theme: pinpress`.
* Save your changes.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in Terminal and typing `bin/grav clear-cache`.

Once this is done, you should be able to see the new theme on the frontend. Keep in mind any customizations made to the previous theme will not be reflected as all of the theme and templating information is now being pulled from the **pinpress** folder.
