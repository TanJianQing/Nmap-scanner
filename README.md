This is a python file that helps you detect if any Nmap scans are being done on your machine. It is built mainly off pyshark.py, and can be used to analyse both real-time threats, or data stored in a pcap file.

The Nmap scanner will show the Source IP addresses (IP address of the external party scanning you), Source Ports (ports external party are using for the scan), and Destination Ports (your ports being scanned by external party).

Parameters can be adjusted to your own preference. To use this in real time, just keep it continuously running, and any suspicious behaviour will be printed out in real time. Otherwise, you can load a .pcapng file into this scanner by adjusting the file_to_read variable to the file's directory.

Give it a try!


Made by Tan Jian Qing, credits to pyshark.py for their functions.
