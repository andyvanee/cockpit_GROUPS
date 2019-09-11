# Groups Management UI Addon for Cockpit

Cockpit: https://github.com/agentejo/cockpit

**NOTE:** I've updated this addon to work with cockpit versions AFTER the big menu overhaul.
If you are running an older cockpit installation BEFORE that menu overhaul you might want to install an older version of this addon. 
You can get it here: https://github.com/serjoscha87/cockpit_GROUPS/releases/tag/v1.0
Please note that this old version won't be supplied with fixes. You are better off updating cockpit to the latest release.

**Changelog**

_11th Sep 2019:_ 
  - Updated for the most current cockpit version **as of today** (commit cef5ee6c16d780b81ba3edc0b4a18129de3452fe)
    - added one new var ("media.path") in the group creation form
    - "Also create" ... now works again (including the password field)
    - "Also create a Collection..." got the possibility to set the new/duped collection's name 
    - Addon now integrates with the new cockpit menu

_Feb 2019:_ 
  - Now there is a "MongoDB Patch" branch (https://github.com/serjoscha87/cockpit_GROUPS/tree/mongodb-patch). Thanks to panosru.

_Sep 2018:_  
  - when configuring ACLs the groups available will be shrinked to a smaller and less space using layout  
  - added singleton to group ACL config mask  
  - Now a group password can be set due the group creation "process"
  - added some more ACLs for management of singletons
  - added shrink view of group cards for singletons and collections
  - when creating a new group now by default the group vars are set

**Screenshot** (a bit outdated):

![Groups Management UI Addon for Cockpit](https://raw.githubusercontent.com/serjoscha87/cockpit_GROUPS/7d6c2f807602186f785ffdb7b064fce62dbffc06/cockpit_groups.jpg)

## Installation

put the "Groups" dir of this repository to < your-docroot >/cockpit/addons/.

## Other projects according to cockpit
https://github.com/serjoscha87/cockpit_GroupBoundAssets  
https://github.com/serjoscha87/cockpit_ApiTester
