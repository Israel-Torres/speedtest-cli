speedtest-cli RR (Re-wRite)
=============

Command line interface for testing internet bandwidth using
speedtest.net - only outputs CSV style output for scripting
and reporting usage.

Versions
--------

speedtest-cli RR 0.3.2.1 works with Python 2.4-3.4 (Re-wRitten with 2.7.6)

Installation
------------

    curl -Lo speedtest-cli.py https://raw.githubusercontent.com/sivel/speedtest-cli/master/speedtest_cli.py
    chmod +x speedtest-cli.py

Usage
-----

   ./speedtest-cli

    Output will appear as:
    "20150722:08:01:54","tw telecom holdings (207.114.182.222)","Hostspace networks LLC (Los Angeles, CA) [97.77 km]","14.859 ms","5.10 Mbit/s","5.16 Mbit/s"

    Header is as follows:
    "Date","fromLocation","toLocation","Latency","Download","Upload"

Notes
-----
    I had to splap this together and didn't want to pipe it through a bunch of tools to get it to have it output the way I needed it. I simply took out the things I didn't need. :)
    
