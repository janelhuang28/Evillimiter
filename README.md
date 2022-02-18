# Evillimiter
Blocking or limiting devices within a network. Evillimiter is a tool that is used to block or limit network devices. 

## Setup

1. Clone the repo with: ``git clone https://github.com/bitbrute/evillimiter.git``
2. Setup the installations: ``cd evillimiter && sudo python3 setup.py install``
3. Run ``sudo evillimiter``

## To run
1. Scan for hosts in the network with ``scan``
2. Display hosts ``hosts`` (use ``--force`` if table can't fit)
3. Limit the devices with ``limit 1,2 200kbit``
4. Block devices with ``block 2 ``

![image](https://user-images.githubusercontent.com/39514108/154596493-3f420597-b86b-45b5-b6a5-9a91ff2809a7.png)
