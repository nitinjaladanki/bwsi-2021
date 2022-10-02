# The Radiant Rainbow Squids - Nitin Jaladanki

This code package contains a simulated Bluefin Sandshark with front seat processor, and a backseat processor. The front seat and back seat can be run on different machines within the same network.

# How to use
Start front seat first!

To start front seat:
python BWSI_FrontSeat.py <port>

The <port> argument is optional, and defaults to 8042

To start the back seat:
python BWSI_BackSeat.py <ip> <port>

Both <ip> and <port> are optional, and default to 127.0.0.1 and 8042. The IP address has to match the IP address of the front seat, and the port has to match the port given to the front seat.


