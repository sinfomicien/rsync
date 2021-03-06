rsync Cookbook CHANGELOG
========================
This file is used to list changes made in each version of the rsync cookbook.

v0.8.8 (2015-05-07)
-------------------
- [#15] Add incoming/outgoing chmod options
- [#16] Add prexfer/postxfer exec commands
- [#14,#17] Support Chef 12

v0.8.6 (2014-09-30)
-------------------
- [#11] Fixes to allow rsync daemon to be started if not up.

v0.8.4
------
### Improvement
- **[COOK-3580](https://tickets.chef.io/browse/COOK-3580)** - Add Test Kitchen, Specs, and Travis CI


v0.8.2
------
### Improvement
- **[COOK-3153](https://tickets.chef.io/browse/COOK-3153)** - Add `refuse_options` parameter to `rsync_serve`

### Bug
- **[COOK-2874](https://tickets.chef.io/browse/COOK-2874)** - Support chkconfig
- **[COOK-2873](https://tickets.chef.io/browse/COOK-2873)** - Allow setting value to false in `rsyncd.conf`

v0.8.0
------
* [COOK-878] - Add LWRP for rsyncd.conf and server recipe

v0.7.0
------
* Initial released version
