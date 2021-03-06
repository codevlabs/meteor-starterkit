## Changelog

### October 3rd, 2014
- Refactored to work with Meteor 0.9+
- Remove Jasny Bootstrap and added custom built CSS3 mobile nav menu
- Modularized contact form to be a separate package
- Replaced fontawesome with ionic icons

### August 20th, 2014
- Bugfix for Iron Router bugs when trying to add / remove meteorite packages
- Changed ```font-awesome``` package to ```fontawesome4``` so that it is loaded locally and is more offline compatible

### August 14th, 2014
- Added a nice sliding in menu instead of the dropdown to make it seem more native (Issue #1)
- Added in a header that includes the user's username
- Added in a helper to get the username
- Changed styling to have a bottom border
- Added a demo url

### August 1st, 2014
* Updated to Meteor 0.8.3
* Added styling for iron-router-progress spinner on the right
* Added a '/slow' route to test slower connections. Thanks [Sacha Greif](http://crater.io/comments/XN6ZJ6Kca3q2qTT7m)

### July 28th, 2014

* Updated BootstrapValidator to be the latest version from v0.3.2 to v0.5.0, currently points to my fork for the updates
* Modified contact form to work with the newer version and simplifies it
* Added loading spinner via Spin package
* Added responsive variables (Thanks [Differential](https://github.com/Differential/meteor-boilerplate/blob/master/client/stylesheets/variables.less))
* Replaced auto-nprogress with iron-router-progress
* Added LESS variables for iron-router-progress styling
