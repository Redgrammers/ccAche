# ccAche
ccAche is a simple bash program (turned executable) that can instantly disapparate caches for easy website development. Installation is simple for beginners and it can be used on the fly. Just type in `ccAche` and you're good to go!
# Installation
To install ccAche, just clone the repository and run the setup script, like so:
```
git clone https://github.com/Redgrammers/ccAche
. ccAche/setup
```
# Usage
Currently (as of v1.0) ccAche comes with 0 options whatsoever; `ccAche --help` and `man ccAche` are expected to appear in v1.1, and specification options are expected to arrive in v1.2.
# Hackery
If you want to hack away at the source on your computer, it's actually very simple. If you've run the setup script before, you will need to remove the file, like so:
```
sudo rm -f /bin/ccAche
```
Then you can modify `dev/ccAche-stable-*` or `cp` a new test file.
# Snapshots (development versions)
If you want to help us develop, there is a periodically updated `dev/snapshots` folder, containing all the development versions. The latest can be found as `dev/snapshots/latest.snapshot`; any snapshot can be found at `dev/snapshots/v<future version number>s<snapshot number>.snapshot`. For example, snapshot 3 of the development of version 1.5.1 would be found at `dev/snapshots/v1.5.1s3.snapshot` (not that there is a v1.5.1s3 snapshot). To test the latest snapshot, first set it up normally:
```
cd ccAche
. setup
```
Then delete the actual binary file:
```
sudo rm -f /bin/ccAche
```
Finally, run the DownLoad Snapshot (DLS) setup file:
```
. setup-dls
```
We would love to recieve bug reports and pull requests to help complete the next major update!
