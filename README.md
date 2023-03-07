# firefox-sidebery-dark-css
this will enable a dark firefox theme for both the browser itself as well as the sidebery addon.

![screenshot](https://user-images.githubusercontent.com/107621826/223304582-bc9f91ed-89bd-4b66-a6b8-412fef3b617f.png)


sidebery is an firefox addon that move tabs to the side of the browser window

how to install

install firefox color addon
https://addons.mozilla.org/en-US/firefox/addon/firefox-color/

enable firefox color dark theme
go to https://color.firefox.com/?theme=XQAAAAIXAQAAAAAAAABBqYhm849SCia2CaaEGccwS-xMDPrzuMg6Caq-qy5QgqeHG4K15QeDoRokmgjiM6AAxM3X9F70ZoGsfXBn8NHNS5cg5bOxiZSXXtNHAmSATvihGNKNxiTiEnexQhqSYLAqnwGNkTnfQgoKka-_YqopxOxOs8_fR-7sdV26-tcc0s3JFWXBuuGv5he5nFvCu0xX1Fp2vTc8_eR4Xnzr1L6-SozT_-1tVAA
or create your own theme on color.firefox.com

install sidebery addon
https://addons.mozilla.org/en-US/firefox/addon/sidebery/

open sidebery setting > styles editor
add content of sidebery-custom-css.css to 'write custom css here' on the right

change background color, title color, sub-title color and label color values in the middle and set all four settings to 'on'


remove firefox view button
https://support.mozilla.org/en-US/kb/how-set-tab-pickup-firefox-view#w_how-do-i-remove-firefox-view-from-the-tabs-bar

go to about:config in firefox and set toolkit.legacyUserProfileCustomizations.stylesheets to 'true'

go to about:profiles in firefox
open root directly of your currently active firefox profile by clicking open folder button
create folder named 'chrome'
put provided userChrome.css file into chrome folder

restart firefox


tested on firefox beta 111.0
