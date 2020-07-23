# DiviNetworkSnapshots
A microsite to download the latest blockchain snapshots for Divi


# Autodeployment on Server
###### (Super simple:)

1. Merge changes to master

(1½. if user is not already www-data, then: `sudo su www-data`)

2. On server `git fetch --all && git checkout --force master && git pull origin master`
