# LangBench CPython 3.8.1 Instrumentation
Use appropriate branch to build different instrumentations.
Build instructions are same as CPython.
See README.rst for original CPython README.

## Enabling rdpmc
sudo sh -c 'echo 2 > /sys/bus/event_source/devices/cpu/rdpmc'
