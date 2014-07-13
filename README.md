SysSnapSum
==========

System Snapshot Utility Summary Report

This script summarizes and reads output from the sys-snap.sh script, which can be downloaded and run with this one-liner:

cd /root && wget 'https://ssp.cpanel.net/SysSnap/sys-snap.sh'; chmod -v +x sys-snap.sh; nohup sh sys-snap.sh &

To use sys-snap-sum.sh, (for example in folder 13):

cd /root/system-snapshot/13

sh <(curl -s https://raw.githubusercontent.com/cPMarco/cpm/master/sys-snap-sum.sh)

The subscreens are all piped to less
Use 'q' to exit less, and CNTRL-C to cancel out of program

The main commands are mostly one-liners.  If you read the code, you can use (copy/paste) them individually.
