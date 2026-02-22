# ffbasictheme
This theme provides a near native look when used with the basic (non DWM) titlebars.

This is NOT a theme that should be used with the normal DWM titlebars, and instead should be used with DWM disabled or with a program that makes the basic frames render such as BasicThemer2. This theme only works as intended at 100% scale, but I'm currently in the process of adding support for 125% scale (titlebar buttons are blurry, when maximized the restore button disappears).

### IMPORTANT:
If your screen size is a size other than 1080p, go into the CSS file and change the numbers for the lines starting with @media. They are in rems (to avoid Firefox interface scaling), so you'll have to multiply your screen size in pixels by 0.0625 to get the size in rems.

## Install
To install this, open about:support, open the profile folder, and copy the chrome folder into the profile folder.

If the theme doesn't apply, go to about:config and set toolkit.legacyUserProfileCustomizations.stylesheets to true.

## Screenshot
<img src="basicfirefox.PNG">
