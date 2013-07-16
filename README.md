### Litecoin Reference Client Git Repo

## Master branches
The master-\* branches contain the mainline commit history of each currently supported major version of Litecoin.

 master-0.6

 master-0.8

 master-0.9

## Archival development history branches
These are generally old archival branches kept for historical purposes.

 devhistory-0.5 - previously known as coblee/litecoin-old/master

 devhistory-0.8.3.x - dev history of 0.8.x prior to the rebase for official release in master-0.8

 devhistory-0.9.x.x - dev history of 0.9.x will be frozen here when it is rebased into master-0.9

## Release Branches
Generally we keep only release branches that actually diverged from master, where the release was tagged from the branch itself.
Whenever possible we will try to make gitian builds directly from a GPG signed tag in master-0.\* branch, and we try to avoid
making releases from side branches.

 ltc-0.6.3

## Experimental/Topic Branches
Branches here may be created and deleted at any time as they become obsolete or merged into other branches.
Use the prefix "exp-" to keep them nicely bunch together in branch listings.

 exp-awesomecoin - rapid development, messy branch of next major release.

 exp-btc09backports - Backports of Bitcoin-0.9 commits

 exp-mark10 - Litecoin specific patches from exp-<codename> squashed/cleaned

 exp-mark10b - Combined candidate branch that later becomes master-0.8

 exp-mark10b-cc - 0.8.3.5 with Coin Control

 exp-mark10b-ccsec - 0.8.3.5 with Coin Control and sipa's secp256k1

## Old/Legacy Branches
Old miscellaneous stuff that we need to keep for some reason is prefixed with "old-"
so they are grouped together in the branch listing.

 old-electrum-obsolete - might be useful one day if someone decides to modernize Electrum support
