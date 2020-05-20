# ARM-Security-Analysis

This project is a security analysis of IoT Fitness devices using ARM Cortex M0 Architecture.

# Research Report Available

- Shreyas-Shetty-Git-Report.pdf

# Install packages (Bluepy, CRC)

Command: pip install -r packages.txt

# Connect to MiBand

1. Turn on your Bluetooth
2. Unpair you MiBand2 from current mobile apps
3. Find out your MiBand3 MAC address
-  Command: sudo hcitool lescan
4. Authenticate Linux Syster with Mi Band 3 device
-  Command: python main.py MAC_ADDRESS --init

# BLE glitch issues? Try command below

- Command: sudo hciconfig hci0 reset
