# Lightweight YouTube Channel Widget

Author: Daniel Jonsson  
License: GPL version 3

This is a slimmed down fork of the WordPress plugin
[youtube-channel](http://wordpress.org/plugins/youtube-channel/) which is
written by [Aleksandar Urošević](http://urosevic.net/). See
[readme.txt](readme.txt) for the WordPress metadata README file.

## Codebase comparison

|     | Lightweight YouTube Channel Widget 10.0  | YouTube Channel 2.4.1.3 |
| --- | ---------------------------------------- | ----------------------- |
| PHP LOC | 586 | 1849 |
| PHP SLOC | 415 | 1289 |
| WordPress plugin dependencies | - | [Redux Framework](http://reduxframework.com/) |
| JavaScript dependencies | - | [jQuery](http://jquery.com/), [FitVids.JS](http://fitvidsjs.com/), [Magnific Popup](http://dimsemenov.com/plugins/magnific-popup/) |
| JavaScript w/ jQuery, minimized * | 0 B | 119.8 kB † |
| JavaScript w/o jQuery, minimized | 0 B | 24.0 kB ‡ |
| CSS, minimized | 1.1 kB § | 7.1 kB ‖ |

\* jQuery version 1.11.1 bundled with WordPress 4.1.  
† 95807 + 22012 + 1746 + 270 = 119835  
‡ 22012 + 1746 + 270 = 24028  
§ 1139 = 1139  
‖ 5998 + 1139 = 7137

Note, SI unit prefixes are used, where k = kilo = 1000.
