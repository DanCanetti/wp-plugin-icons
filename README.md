# Wordpress Plugin Icon Font
A font which includes some of the most popular WordPress Icons.<br />
[View Demo](https://dancanetti.github.io/wp-plugin-icons/)

# Installing the icons
### yarn
```
yarn add wordpress-icon-font
```
### Direct download
[Download fonts and stylesheets](https://github.com/DanCanetti/wp-plugin-icons/archive/master.zip) and unzip the downloaded file.

### Install
* Copy the font files to your fonts/webfonts directory
* Copy the CSS files (To save loading times I reccommend only copying the minified file) to your css directory
* Include the css file in the ```<head>``` of your project
* You're should be ready to use the icons now
* **Don't forget to apply the ```aria-label="Plugin Name"``` if you're using the icon on it's own**

# Using the icons
``` html
<i class="wp-plugin-yoast"></i> Yoast SEO
<span class="wp-plugin-ithemes-security" aria-label="iThemes Security"></span>
<a href="#" class="wp-plugin-jetpack"></a>
```

# Current icons
* Advanced Custom Fields
* Contact Form 7
* Divi Builder
* iThemes Security
* Jetpack
* LearnPress
* Yoast SEO
* Askimet
* W3 Total Cache
* WP Smush
* Wordfence
* Woo Commerce
* Updraft
* Duplicator
* Ninja Forms

# Requesting new icons
[Request Icons Here](https://github.com/DanCanetti/wp-plugin-icons/issues) and add the label 'Icon Request'

# Changelog
## Version 1.0.0 ##
* Initial Version

## Version 1.0.1 ##
* Added scss files for install
* Added these icons:
    * Askimet & Alt
    * Advanced Custom Fields Alt
    * W3 Total Cache
    * WP Smush
    * Wordfence
    * Woo Commerce
    * Updraft
    * Duplicator
    * Ninja Forms

## Version 1.0.2 ##
* Now available as yarn package

# Updates as/when I get time
* Creating a better demo page
   * Include recommended Aria Labels for each icon
* Adding more icons

# ☕ Buy me a pint
If you liked Wordpress Plugin Icon Font, please consider buying me a coffee.
[Thank you for your support!](buymeacoff.ee/MfXCoSEBF)

# License
Free to use however you like. Go nuts!<br />
If you're using wp-plugin-fonts, let me know on [Twitter](https://twitter.com/Dan_Canetti) I'd love to see it in action!
