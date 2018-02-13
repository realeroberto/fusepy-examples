# fusepy-examples

Examples for the fusepy library (a work in progress).

### factors.py

Only admits integers as folder names, and populates the folder themselves with the integer factors.

Usage:


        $ mkdir /tmp/loopback /tmp/mountpoint
        $ python factors.py /tmp/loopback /tmp/mountpoint &

        $ mkdir /tmp/mountpoint/54334
        $ ls /tmp/mountpoint/54334
        1  14  2  27167  3881  54334  7  7762
