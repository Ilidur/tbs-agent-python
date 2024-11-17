# Agent Python

CRSF client in Python. Works via TCP or UART connections.
Can be used to connect to WiFi module on Crossfire.
It can sniff broadcast frames, receive paramters, etc.

## Requirements
It requires Python 3.4 or above to run.

To install all the dependencies:
```
pip install -r requirements.txt
```
## Usage
To launch menu via UART:
```
./crsf.py --menu
```

To launch logger via TCP:
```
./crsf.py --tcp
```

To launch logger via UART:
```
./crsf.py
```

Parameters such as `SERIAL_PORT` might need to be tweaked manually (at the top of the script).
