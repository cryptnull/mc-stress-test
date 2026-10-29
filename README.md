# Minecraft Network Testing Tool

Educational stress-testing script for Minecraft servers. Use only on servers you own or have permission to test.

## Usage

1. Grant permissions:
   chmod 777 *

2. Run the script:
   ./minecraft <IP/DOMAIN> <PORT> [duration] [threads] [sockets] [burst] [intensity] [packetsize]

### Parameters
* <IP/DOMAIN> - Target address
* <PORT> - Target port
* [duration] - Time in seconds
* [threads] - Concurrent threads
* [sockets] - Sockets per thread
* [burst] - Burst rate
* [intensity] - Intensity level
* [packetsize] - Packet size

Disclaimer: For educational purposes only. The author is not responsible for misuse.
