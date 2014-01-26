# Chef Cookbooks for OS X

## You've automated your servers. Now automate your workstation.

This organization contains various cookbooks targeted at [Chef](https://getchef.com/) users who want to automate their Mac OS X workstations. It was inspired by the [Pivotal Sprout](https://github.com/pivotal-sprout/) project, but Sprout assumes you want to manage your workstation using Chef Solo running under your user ID. The cookbooks & recipes in here have no such restriction.

## What this organization does not contain

Cookbooks out in the community that already have cross-platform support, including for Mac OS X, are not included here. This organization's repositories contain, and will continue to contain, *only* cookbooks that work exclusively on Mac OS X.

## Related cookbooks

Besides Pivotal Sprout, there are lots of great community cookbooks used to set up other aspects of your Mac OS X system. Some of them are used here as dependencies. Among them:

* [dmg](http://ckbk.it/dmg), for managing and installing applications off DMGs
* [mac_os_x](http://ckbk.it/mac_os_x), some LWRPs for managing plist files
* [xquartz](http://ckbk.it/xquartz), for installing XQuartz (X11)
* [1password](http://ckbk.it/1password), for installing the 1Password password manager

## Authors and Contributors

This project was started by Julian Dunn (@juliandunn), who works at Chef Software. Contributions are welcome! If you have an OS X-exclusive cookbook that you no longer wish to maintain, or want others to help collaborate with outside of your personal GitHub namespace, please get in touch and we can talk about getting it transferred to this organization.
