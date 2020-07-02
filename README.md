# GalaxyBuds-BatteryLevel
Simple python script to read battery values and the current wearing status from the Samsung Galaxy Buds (2019)

## Requirements

This script requires **Python 3.x**!

You need to install PyBluez:
```
pip install PyBluez
```

## Showcase

```
❯ python3 buds_battery.py -h
usage: buds_battery.py [-h] [-w] [-v] MAC-Address

Read battery values of the Samsung Galaxy Buds (2019)

positional arguments:
  MAC-Address           MAC-Address of your Buds

optional arguments:
  -h, --help            show this help message and exit
  -w, --wearing-status  Print wearing status instead
  -v, --verbose         Print debug information
```
```
❯ python3 buds_battery.py EC:AA:25:07:49:1B
90,75
```
```
❯ python3 buds_battery.py EC:AA:25:07:49:1B -w
Both
```
