# Change Log

## 2.4.0
* To free up disk space, don't back up file and remove simulator installer file

## 2.3.1
* Fix path to `xcodebuild` for runFirstLaunch

## 2.3.0
* Fix for determining next version (https://github.com/Roblox/chef-xcode/issues/2)
* Newer versions of Xcode provides `-runFirstLaunch` method for installing dependent packages
* Rename resource `version` to `id` as the version should be deciphered from the package

## 2.2.0
* Detach fork from upstream
* Clean up docs
* Reconfigure resource

## 2.1.2
* Fix path for xcode-select
* Update versions in example test databags

## 2.1.1
* Fix ruby_block by splitting into 2 blocks for post_install

## 2.1.0
* Modify app install for license and multi install (replaced with suffix)
* Add ability to install simulator

## 2.0.0
* Re-write of the cookbook to be a custom resource and allow for multiple Xcode installs on a single node
* Removed command line tool installation as that is handled by build-essentials cookbook

## 1.3.0
* Add El Capitan support
* Update Xcode version for Yosemite

## 1.2.0
* Update Xcode version for Mountain Lion
* Add Mavericks support
* Add Yosemite support

## 1.1.2
* Added Lion support

## 1.1.0
* Add Mountain Lion support

## 1.0.0
* Initial release of xcode
